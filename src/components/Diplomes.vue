<script setup>

import DiplomaItem from './DiplomaItem.vue';


const diplomes = [
    {
        title: "LICENCE in development internet/intranet at Ecole de Management et d'innovation Technologique (EMIT) Fianarantsoa",
        year: "2023"
    },
    {
        title: "BACC C at Lycée Privée Stella Maris La Salle Toamasina",
        year: 2019
    }
]


</script>

<template>

    <div>

         <div class="text-xl font-bold text-white">Studies and Diplomas</div>

        <DiplomaItem v-for="d in diplomes" :title="d.title">{{ d.year }}</DiplomaItem>


    </div>


    
</template>