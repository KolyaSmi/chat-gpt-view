<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <HeroBlock></HeroBlock>
    <CompBlock></CompBlock>
    <BigCartBlock></BigCartBlock>
    <FeatureBlock></FeatureBlock>
    <FeatureBottomBlock></FeatureBottomBlock>
    <CTA></CTA>
    <BlogBlock></BlogBlock>
    <EarlyAccess></EarlyAccess>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import HeroBlock from '@/components/HeroBlock.vue';
import CompBlock from '@/components/CompBlock.vue';
import BigCartBlock from '@/components/BigCartBlock.vue';
import FeatureBlock from '@/components/FeatureBlock.vue';
import FeatureBottomBlock from '@/components/FeatureBottomBlock.vue';
import CTA from '@/components/CTA.vue';
import BlogBlock from '@/components/BlogBlock.vue';
import EarlyAccess from '@/components/EarlyAccess.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    HeroBlock,
    CompBlock,
    BigCartBlock,
    FeatureBlock,
    FeatureBottomBlock,
    CTA,
    BlogBlock,
    EarlyAccess
  }
}
</script>
