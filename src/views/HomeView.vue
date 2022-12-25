<template>
    <div class="home">
    <HeaderTokol/>
    
    <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel :items-to-show="1">
        
        <slide class="single-hero-items set-bg" style="background-image: url('/img/hero-1.jpg')">
            <div class="container" style="height: 500px;">
                <div class="row">
                    <div class="col-lg-5">
                        <span>Bag,kids</span>
                        <h1>Black friday</h1>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                        </p>
                        <a href="#" class="primary-btn">Shop Now</a>
                    </div>
                </div>
            </div>
        </slide>
        <slide class="single-hero-items set-bg" style="background-image: url('/img/hero-2.jpg')">
            <div class="container" style="height: 500px;">
                <div class="row">
                    <div class="col-lg-5">
                        <span>Bag,kids</span>
                        <h1>Black friday</h1>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                        </p>
                        <a href="#" class="primary-btn">Shop Now</a>
                    </div>
                </div>
            </div>
        </slide>
        <slide class="single-hero-items set-bg" style="background-image: url('/img/hero-3.jpg')">
            <div class="container" style="height: 500px;">
                <div class="row">
                    <div class="col-lg-5">
                        <span>Bag,kids</span>
                        <h1>Black friday</h1>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                        </p>
                        <a href="#" class="primary-btn">Shop Now</a>
                    </div>
                </div>
            </div>
        </slide>
    <template #addons>
      <navigation />
      <pagination />
    </template>
  </carousel>
    </section>
    <!-- Hero Section End -->

    
    </div>
</template>



<script>
    // @ is an alias to /src import HelloWorld from '@/components/HelloWorld.vue'
    import HeaderTokol from '@/components/HeaderTokol.vue';
    // import carousel from 'vue-owl-carousel';
    import 'vue3-carousel/dist/carousel.css';
    import { Carousel, Slide, Navigation, Pagination } from 'vue3-carousel';


    export default {name: 'HomeView', components: {
            HeaderTokol,
            Carousel,
            Slide,
            Navigation,
            Pagination,
        }}
</script>