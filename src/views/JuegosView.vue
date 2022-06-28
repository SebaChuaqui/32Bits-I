<template>
    <div>
        <juegos-list></juegos-list>
    </div>
</template>

<script>
import JuegosList from '@/components/juegos/JuegosList.vue'
export default {
    name: 'juegos-view',
    data: function(){
        return {}
    },
    components: {
        'juegos-list': JuegosList
    },
}
</script>

<style scoped>
    
</style>