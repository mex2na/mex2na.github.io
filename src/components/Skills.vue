<script setup>
import SkillItem from './SkillItem.vue';
import js from "../assets/images/js.jpg";
import python from "../assets/images/python.jpg"
import node from "../assets/images/nodejs.jpg"
import symfony from "../assets/images/symfony.jpg"
import vue from "../assets/images/vuejs.jpg"
import react from "../assets/images/reactjs.jpg"
import tailwind from "../assets/images/tailwindcc.jpg"

let skills = [{image:js, title:"JS"},{image:python, title:"Python"},{image:node, title:"nodejs"},{image:symfony, title:"Symfony"},{image:vue, title:"Vue"},{image:react, title:"React"},{image:tailwind, title:"TailwindCSS"}];



</script>



<template>
    <div>
        <div class="text-xl font-bold text-white py-2">Programming languages and Frameworks</div>
        <div class="flex flex-wrap">
            <SkillItem v-for="s in skills" class="animate-pulse  mr-3" :image="s.image">
                {{ s.title }}
            </SkillItem>
        </div>



    </div>


</template>