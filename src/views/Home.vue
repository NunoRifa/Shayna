<template>
  <div class="home">
    <HeaderShyna />
    <HeroShyna />
    <BannerShyna />
    <InstaShyna />
    <LogoShyna />
    <FooterShyna />
  </div>
</template>

<script>
  // @ is an alias to /src
  // import HelloWorld from "@/components/HelloWorld.vue";
  import HeaderShyna from "@/components/HeaderShyna.vue";
  import HeroShyna from "@/components/HeroShyna.vue";
  import BannerShyna from "@/components/BannerShyna.vue";
  import InstaShyna from "@/components/InstaShyna.vue";
  import LogoShyna from "@/components/LogoShyna.vue";
  import FooterShyna from "@/components/FooterShyna.vue";

  export default {
    name: "Home",
    components: {
      HeaderShyna,
      HeroShyna,
      BannerShyna,
      InstaShyna,
      LogoShyna,
      FooterShyna,
    },
  };
</script>
