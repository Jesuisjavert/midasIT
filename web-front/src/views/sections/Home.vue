<template>
  <v-container
    id="home"
    class="pt-12 pb-0 px-0"
    fluid
    tag="section"
  >
    <home-slider />
    <home-headline />
</v-container>
</template>

<script>
  export default {
    name: 'Home',

    components: {
      HomeSlider: () => import('@/components/base/HomeSlider'),
      HomeHeadline: () => import('@/components/base/HomeHeadline'),
    },
  }
</script>
