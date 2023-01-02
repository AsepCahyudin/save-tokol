<template>
    <div class="home">
    <HeaderTokol/>
    <CarouselTokol/>
    <BannerTokol/>
    

    
    </div>
</template>



<script>
    // @ is an alias to /src import HelloWorld from '@/components/HelloWorld.vue'
    import HeaderTokol from '@/components/HeaderTokol.vue';
    import CarouselTokol from '@/components/CarouselTokol.vue';
    import BannerTokol from '@/components/BannerTokol.vue';
    

    export default {name: 'HomeView', components: {
            HeaderTokol,
            CarouselTokol,
            BannerTokol,
        }
    }
</script>