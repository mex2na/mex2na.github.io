<script setup>
    import photo from "../assets/images/photo_CV.jpg" 
    import data from "../assets/data.json"

    const {profile} = data
    
    


</script>
<template>

<div class="flex-col gap-5  text-black p-2">

    <div class="flex justify-center pb-2">
        <img :src="photo" alt="pdp" class="w-40 object-fill h-40 rounded-full">
    </div>
    
    <div>
        <p class="text-2xl font-medium text-center">{{ profile.name }}</p>
        <p class="text-base text-center">{{profile.lastName}}</p>
  </div>

    <div class="flex  px-10 mt-5">
        <span class="text-sm text-left  pb-5 border-black border-b-2 px-6 ">{{profile.profilDescription}}</span>
    </div>

</div>

    
</template>