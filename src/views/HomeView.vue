<template>
    <div class="home">
    <HeaderTokol/>
    </div>
</template>

<script>
    // @ is an alias to /src import HelloWorld from '@/components/HelloWorld.vue'
    import HeaderTokol from '@/components/HeaderTokol.vue'

    export default {name: 'HomeView', components: {
            HeaderTokol
        }}
</script>