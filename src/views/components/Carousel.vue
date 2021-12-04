<template>
  <section class="section section-lg section-shaped overflow-hidden my-0">
    <div class="shape shape-style-1 shape-default shape-skew">
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
      <span></span>
    </div>
    <div class="container py-0 pb-lg">
      <div class="row justify-content-between align-items-center">
        <div class="col-lg-5 mb-5 mb-lg-0">
          <h1 class="text-white font-weight-light">
            Screenshots and game play
          </h1>
          <p class="lead text-white mt-4">
            Math is everywhere around us, whether we realize it or not. Every
            time we conduct an internet search, order something online, or
            automatically get recommendations for products that we are looking
            for.
          </p>
          <!-- <a href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
                       class="btn btn-white mt-4">See all components</a> -->
        </div>
        <div class="col-lg-4 mb-lg-auto">
          <div
            class="rounded shadow-lg overflow-hidden transform-perspective-right"
          >
            <b-carousel id="carousel1" controls :interval="2000" indicators>
              <!-- Text slides with image -->
              <b-carousel-slide
                v-for="n in 9"
                :key="n"
                :img-src="`mathechnique/sample-${n}.png`"
              ></b-carousel-slide>
            </b-carousel>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
import { BCarousel } from 'bootstrap-vue/esm/components/carousel/carousel';
import { BCarouselSlide } from 'bootstrap-vue/esm/components/carousel/carousel-slide';

export default {
  components: {
    BCarousel,
    BCarouselSlide
  }
};
</script>
<style></style>
