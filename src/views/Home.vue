<template>
 <div class="row">

 <div class="col-2"></div>
 <div class="col-7">
     <instagram-card />
     <InstagramCard />
 </div>
 <div class="col-3">
 ... ovdje ide desni stupac!
 </div>
 </div>
</template>



<script>
// @ is an alias to /src
import InstagramCard from '@/components/InstagramCard.vue';

export default {
    name: 'home',
    components: {
        InstagramCard, //kljuc i vrijednost? ovo napisano je isto sto i InstagramCard: InstagramCard
    },
};
</script>
