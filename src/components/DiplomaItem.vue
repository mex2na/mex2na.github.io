<script setup>

let props = defineProps({
    title:"string"
})



</script>
<template>

    <div class="flex justify-between py-2 items-center">

        <p class="w-56">
            {{ props.title }}
        </p>   
        <p>
           done in <slot></slot>
        </p>


    </div>

</template>