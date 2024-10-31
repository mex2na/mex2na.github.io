<script setup>

let props = defineProps({
    post: String,
    duree: String
})

</script>

<template>

    <div class="flex-col justify-center py-2">
        <div class="flex justify-between">
            <p class=" font-bold w-56">{{props.post}}</p>   
            <p class=" border-l-2 pl-2">
               {{ props.duree }}
            </p>   
        </div>
        <div class="text-center font-semibold">
            <slot></slot>
        </div>

    </div>


</template>