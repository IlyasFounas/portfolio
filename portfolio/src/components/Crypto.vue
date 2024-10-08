<script setup>
import { ref, onMounted } from 'vue';
import axios from 'axios';
//import BarChart from "@/components/pages/BarChart.vue";

//import nav from './components/_partials/_header.vue';
// Déclare une variable réactive pour stocker les données
const info = ref(null);
const solInfo = ref(null);

// Bitcoin
onMounted(() => {
  axios
      .get('https://api.coindesk.com/v1/bpi/currentprice.json')
      .then(response => {
        info.value = response.data.bpi; // Assigne les données à la variable réactive
      })
      .catch(error => {
        console.error('Error fetching data:', error);
      });
});

//Solana
onMounted(() => {
  axios
      .get('https://api.coingecko.com/api/v3/simple/price?ids=solana&vs_currencies=usd')
      .then(response => {
        solInfo.value = response.data.solana.usd;
      })
      .catch(error => {
        console.error('Error fetching Solana price:', error);
      });
});
</script>

<template>
  <header>
    <navBar/>
  </header>
  <main class="d-flex justify-content-center mt-4" id="experience">
    <div class="card border-success mb-3 rounded" style="max-width: 20rem;">
        <div class="card-header">Bitcoin</div>
        <div class="card-body">
            <p class="card-text">
                <div v-if="info">
                <div v-for="currency in info" :key="currency.code" class="currency">
                {{ currency.description }}:
                <span class="lighten">
                    <span v-html="currency.symbol"></span>
                    {{ currency.rate_float | currencydecimal }}
                </span>
                </div>
            </div>
            <div v-else>
                Loading...
            </div>
            </p>
        </div>
    </div>

    <div class="card border-success mb-3 rounded" id="solana" style="max-width: 20rem;">
        <div class="card-header">Solana</div>
        <div class="card-body">
            <p class="card-text">
                <div v-if="solInfo">
                    United States Dollar: ${{ solInfo }}
                </div>
                <div v-else>
                    Loading...
                </div>
            </p>
        </div>
    </div>
  </main>

</template>