<template>
  <main>
    <Features></Features>
    <Integrations></Integrations>
    <Subscribe></Subscribe>
  </main>
</template>

<script>
// @ is an alias to /src
import Features from "@/components/Features.vue";
import Integrations from "@/components/Integrations.vue";
import Subscribe from "@/components/Subscribe.vue";

export default {
  components: {
    Features,
    Integrations,
    Subscribe
  }
};
</script>
