<template>
  <v-content>
    <Hero />
    <Gallery />
    <LatestPost />
  </v-content>
</template>

<script>
import Hero from "../components/Hero";
import Gallery from "../components/Gallery";
import LatestPost from "../components/LatestPost";

export default {
  name: "Home",
//renders hero gallery etc
  components: {
    Hero,
    Gallery,
    LatestPost
  }
};
</script>