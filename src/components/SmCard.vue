<template>
  <div class="about__header-cards">
    <div
      class="about__header-card"
      v-for="(card, index) in smCards"
      :key="index"
    >
      <ul class="about__header-list">
        <li class="about__header-list-line"></li>
        <li class="about__header-list-li">
          <img src="@/assets/orange-ell.png" />{{ smCards[index] }}
        </li>
      </ul>
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
