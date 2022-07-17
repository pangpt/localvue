<template>
  <div class="home">
    <HeaderLocal />
    <HeroLocal />
    <OutterLocal />
    <InstaLocal />
    <PartnerLocal />
    <FooterLocal />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderLocal from '@/components/HeaderLocal.vue';
import HeroLocal from '@/components/HeroLocal.vue';
import OutterLocal from '@/components/OutterLocal.vue';
import InstaLocal from '@/components/InstaLocal.vue';
import PartnerLocal from '@/components/PartnerLocal.vue';
import FooterLocal from '@/components/FooterLocal.vue';

export default {
  name: 'HomeView',
  components: {
    HeaderLocal,
    HeroLocal,
    OutterLocal,
    InstaLocal,
    PartnerLocal,
    FooterLocal,
  },
};
</script>
