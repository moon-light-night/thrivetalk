<template>
  <div class="about__header-cards">
    <div class="about__header-card" v-for="(card, i) in smCards" :key="i">
      <div class="about__card-wrap">
        <p>{{ smCards[i] }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    smCards: [
      'Weight Lifting',
      'Running & Spinning',
      'Pumping Iron',
      'Pumping Iron',
    ],
  }),
}
</script>
