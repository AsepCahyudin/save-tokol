<template>
    <div class="home">
    <HeaderTokol/>
    <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel>

<img src="https://placeimg.com/200/200/any?1">

<img src="https://placeimg.com/200/200/any?2">

<img src="https://placeimg.com/200/200/any?3">

<img src="https://placeimg.com/200/200/any?4">

</carousel>
    </section>
    <!-- Hero Section End -->

    
    </div>
</template>

<script>
    // @ is an alias to /src import HelloWorld from '@/components/HelloWorld.vue'
    import HeaderTokol from '@/components/HeaderTokol.vue';
    import carousel from 'vue-owl-carousel';

    export default {name: 'HomeView', components: {
            HeaderTokol,
            carousel,
        }}
</script>