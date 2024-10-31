<script setup>

   import Profile from './components/Profile.vue'; 
   import Contacts from './components/Contacts.vue';    
   import Languages from './components/Languages.vue';
   import Interests from "./components/Interests.vue";
   import Experiences from './components/Experiences.vue';
   import Diplomes from './components/Diplomes.vue';
   import Skills from './components/Skills.vue';

</script>

<template>

<div class="sm:flex ">

    
    <div id="aside" class=" min-h-screen   sm:w-2/5 bg-[#F8C822]  py-4">
            <Profile/>           
            <Contacts/>
            <Languages/>
            <Interests/>
            
    </div>

    
    <div id="content" class=" w-full sm:w-3/5 p-4">
        <Experiences/>
        <Diplomes/>
       <Skills/>
    </div>

</div>

</template>




