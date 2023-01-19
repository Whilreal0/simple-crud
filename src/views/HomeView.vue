<template>
  <v-main>
    <Todo />
  </v-main>
</template>
<script>
import Todo from "@/components/Todo";

export default {
  name: "home",

  data: () => ({
    //
  }),
  components: {
    Todo,
  },
};
</script>
<style >
body {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
}
</style>