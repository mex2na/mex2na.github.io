<script setup>

//    import { ref } from "vue";
import {languages} from "../assets/data.json";

    

</script>

<template>

    <div id="language" class="px-5">
        
        <div class="text-xl font-bold">Languages </div>

        <div  class="flex justify-between pt-3">
            <div class="textNoir font-bold">{{languages.mg.title}}</div>
        <div>{{languages.mg.level}}</div>
        </div>

        <div class="flex justify-between pt-3">
            <div class="textNoir font-bold">{{languages.fr.title}}</div>
            <div>
                <progress max="100" :value="languages.fr.level" class="custom-progress"> 70% </progress>
            </div>
        </div>

        <div class="flex justify-between pt-3">
            <div class="textNoir font-bold">{{languages.eng.title}}</div>
                <progress max="100" :value="languages.eng.title" class="custom-progress"></progress>
        </div>
    </div>



</template>

<style>
    .custom-progress{
        appearance: none;
        width: 100px;
        border-radius: 10px;
        color: red;
    }

</style>

