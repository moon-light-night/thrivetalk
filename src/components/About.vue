<template>
  <div class="about">
    <div class="about__header">
      <div class="about__header-info">
        <div class="about__header-name">ABOUT US</div>
        <div class="about__header-desc">
          We want to help you thrive! Whether you are just looking for someone
          to talk to, or are struggling with a mental wellness issue we’re here
          to help. Our highly talented therapists can help you with a range of
          issues including relationships, sex, PTSD, depression, social anxiety,
          or even just caring for yourself more.
        </div>
      </div>
      <p class="about__header-text">WE CAN HELP YOU WITH</p>
      <div>
        <SmCard></SmCard>
      </div>
    </div>
    <div>
      <BgCard></BgCard>
    </div>
    <div>
      <DescCard></DescCard>
    </div>
    <div class="about__fact">
      <div class="about__fact-img"><img src="@/assets/linkedin.png" /></div>
      <div class="about__fact-content">
        <div class="about__fact-header">YOU SHOULD ALSO KNOW</div>
        <div class="about__fact-body">
          MDD affects more than 16.1 million American adults, or about 6.7%of
          the U.S. population age 18 and older in a given year. We at
          <span>ThriveTalk</span>
          can help you.
        </div>
        <div class="about__fact-footer">GET HELP NOW</div>
      </div>
    </div>
  </div>
</template>

<script>
import SmCard from './SmCard.vue'
import BgCard from './BgCard.vue'
import DescCard from './DescCard.vue'
export default {
  components: {
    SmCard,
    BgCard,
    DescCard,
  },
}
</script>
