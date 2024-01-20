<script setup>
import LuxuryIcon from "./components/LuxuryIcon.vue";
import SedansIcon from "./components/SedansIcon.vue";
import SuvsIcon from "./components/SuvsIcon.vue";
import TheCard from "./components/TheCard.vue";
</script>

<template>
  <main class="mx-auto flex flex-col p-8 max-w-md sm:max-w-5xl sm:flex-row ">
    <TheCard class="bg-bright-orange text-bright-orange">
      <template #icon><SedansIcon></SedansIcon></template>
      <template #header> Sedans </template>
      <template #body>
        Choose a sedan for its affordability and excellent fuel economy.
        Ideal for cruising in the city or on your next road trip.
      </template>
    </TheCard>
    <TheCard class="bg-dark-cyan text-dark-cyan">
      <template #icon><SuvsIcon></SuvsIcon></template>
      <template #header class="text-white"> SUVs </template>
      <template #body class="text-white">
        Take an SUV for its spacious interior, power, and versatility. Perfect
        for your next family vacation and off-road adventures.
      </template>
    </TheCard>
    <TheCard class="bg-very-dark-cyan text-very-dark-cyan">
      <template #icon><LuxuryIcon></LuxuryIcon></template>
      <template #header> Luxury </template>
      <template #body>
        Cruise in the best car brands without the bloated prices. Enjoy
        the enhanced comfort of a luxury rental and arrive in style.
      </template>
    </TheCard>
  </main>
</template>
