<template>
  <div class="home">
    <h1>This is home</h1>
    <Card/>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";
import Card from "@/components/Card.vue"

export default {
  name: "Home",
  components: {
    Card
  },
};
</script>
