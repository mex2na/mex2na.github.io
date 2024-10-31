<script>

import {interests} from "../assets/data.json"
console.log(interests);


</script>

<template>

    <div class="px-5 pt-3">
        
        <div class="text-xl font-bold">Interests</div>

        <div>
            <p class="text-black">
               {{ interests ?? "Coding, speed typing, reading, slam poetry, basket-ball, watching films/animés/series..." }}
            </p>
        </div>

    </div>


</template>