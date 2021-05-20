<template>
  <div class="content"></div>
</template>
<script>
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  setup() {
    "Mainer";
  },
});
</script>
<style scoped>
.content {
  font-size: 30px;
  height: calc(100vh - 86px);
  /* 86 = header 86 + margin 20 */
  margin: 10px;
  background-color: rgb(55 138 154);
}
</style>
