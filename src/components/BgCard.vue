<template>
  <div class="about__cards">
    <div class="about__card" v-for="(card, i) in bgCards" :key="i">
      <div class="about__card-wrap">
        <img src="@/assets/orange-ell.png" />
        <p>{{ bgCards[i] }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    bgCards: [
      'Physical Healtn',
      'Mental Health',
      'Nutrition',
      'Gymnastics',
      'Crossfit',
      'Aerobics',
    ],
  }),
}
</script>
