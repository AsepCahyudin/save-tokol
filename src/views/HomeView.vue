<template>
    <div class="home">
    <HeaderTokol/>
    <CarouselTokol/>
    

    
    </div>
</template>



<script>
    // @ is an alias to /src import HelloWorld from '@/components/HelloWorld.vue'
    import HeaderTokol from '@/components/HeaderTokol.vue';
    import CarouselTokol from '@/components/CarouselTokol.vue';
    

    export default {name: 'HomeView', components: {
            HeaderTokol,
            CarouselTokol,
        }
    }
</script>