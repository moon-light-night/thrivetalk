<template>
  <div class="about__descs">
    <div class="about__desc-group" v-for="(card, i) in titlesCards" :key="i">
      <div class="about__desc-title">{{ card }}</div>
      <div class="about__desc-text">
        {{ descCards }}
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    titlesCards: [
      'Nutritional Plans',
      'Weight Loss',
      'Mental Peace',
      'Home Training',
      'Work/Life Balance',
      'Cardio',
    ],
    descCards: `Nutritional Facts on some shitty things that you don’t care about and 
        even we don’t , I need to replace this copy.`,
  }),
}
</script>
