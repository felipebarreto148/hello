<template>
  <!-- eslint-disable -->
  <main id="app">
    <a-config-provider>
      <a-button>Teste</a-button>
    </a-config-provider>
  </main>
</template>

<script>
/* eslint-disable */
import { Button as AButton, ConfigProvider as AConfigProvider } from "ant-design-vue";

export default {
  name: "App",
  components: {
    AButton,
    AConfigProvider
  },
};
</script>

<style scoped>
#app {
  display: flex;
  gap: 50px;
}
</style>
