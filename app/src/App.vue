<template>
  <full-page ref="fullpage" id="fullpage">
    <div class="section" id="splash">
      <h1 id="">Leonce's Journey: An AI Art Exhibition</h1>
      <h4 id="names">
        The exploration of the themes of independence and self-discovery in The
        Awakening
      </h4>
      <h6 id="credit">
        Art and literary analysis provided by Christopher Heo & Christopher Feng
      </h6>
    </div>
    <SectionOne class="section" />
    <SectionTwo class="section" />
    <SectionThree class="section" />
    <SectionFour class="section" />
    <SectionFive class="section" />
  </full-page>
</template>

<style scoped>
.fp-watermark {
  display: hidden !important;
}

#names {
  margin-top: auto;
  font-weight: 400;
}

#splash {
  position: relative;
}

#credit {
  font-weight: 400;

  position: absolute;
  bottom: 3rem;
  left: 0;
  right: 0;
}
</style>

<script>
import SectionOne from "./components/SectionOne.vue";
import SectionTwo from "./components/SectionTwo.vue";
import SectionThree from "./components/SectionThree.vue";
import SectionFour from "./components/SectionFour.vue";
import SectionFive from "./components/SectionFive.vue";
export default {
  components: {
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour,
    SectionFive,
  },
};
</script>