<script setup>
    import iconEmail from "../assets/icons/email@1.25x.png";
    import iconLocation from "../assets/icons/location@1.25x.png";
    import iconTel from "../assets/icons/phone@1.25x.png";
    import {contacts} from "../assets/data.json";
</script>

<template>

    <div class="px-5 ">
        
        <div class="text-xl font-bold">Contacts</div>

        <div class="pt-3 flex justify-between items-center gap-5">
            <div>

                <img :src="iconTel" class="rounded-full" alt="tel">
            </div>
            <div class="text-black">{{contacts.tel}}</div>
        </div>

        <div class="pt-2 flex justify-between items-center gap-5">
            <div>
                <img :src="iconEmail" class="rounded-full" alt="email">
            </div>
            <div class="text-black">{{contacts.email}}</div>
        </div>

        <div class="pt-2 flex justify-between items-center gap-5">
            <div>
                <img :src="iconLocation" class="rounded-full" alt="location">
            </div>
            <div class="text-black">{{contacts.location}}</div>
        </div>

       
    </div>




</template>