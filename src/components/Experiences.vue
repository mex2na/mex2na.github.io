<script setup>
    import ExperienceItem from './ExperienceItem.vue';

    const exps = [
        {
            title:"INTEGRATION OF THE FRONT-END PART OF A ONLINE WALLET WEB APP",
            duree: "October - November 2023",
            post: "Dev front-end react at Softab Antananarivo"
        },
         {
            title:"CONCEPTION AND INTEGRATION OF A BASKET-BALL MATCH STATISTICS WEB APP",
            duree: "August - September 2023",
            post: "STAGE Dev fullstack JS (vuejs/express) at Basket-ball ligue Haute Matsiatra"
        }, 
        {
            title:"CONCEPTION AND INTEGRATION OF A MEMBER OF PERSONNAL GESTION WEB APP",
            duree: "June - August 2022",
            post: "STAGE Dev (vanilla JS / php) at Alliance Française de Tamatave"
        },
    ]



</script>


<template>

    <div>
        
        <div class="text-xl font-bold text-white">Professional experiences</div>
        <div>
            <ExperienceItem v-for="exp in exps" :post="exp.post" :duree="exp.duree">{{exp.title}}</ExperienceItem>
        </div>

    </div>



</template>