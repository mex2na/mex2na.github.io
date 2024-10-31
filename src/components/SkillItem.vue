<script setup>
let props = defineProps({
    image:String
})

</script>

<template>

    <div class="flex-col w-24 ">
        <div class="h-2/3">
            
        <img :src="props.image" class="min-w-14"  alt="programming language">
        </div>
        <div class="text-center h-1/3  flex items-center justify-center py-1" >
            <p>
                
            <slot></slot>
            </p>
        </div>
    </div>




</template>