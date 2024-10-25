<script setup>
   import Profile from './components/Profile.vue'; 
   import Contacts from './components/Contacts.vue';    
   import Languages from './components/Languages.vue';
   



</script>

<template>
  
    <div id="aside" class="w-2/5 bg-[#F8C822] md:h-48 md:w-full py-4">
            <Profile/>
            <Contacts/>
            <Languages/>

    </div>

    
    <div id="content" class="w-3/5 md:grow md:w-full">


    </div>


</template>




