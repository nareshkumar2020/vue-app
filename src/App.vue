<template>
  <div class="container">
    <TicTacToe :player="1" />
  </div>
</template>

<script>
import TicTacToe from "tic-tac-toe-library/src/components/TicTacToe.vue";

export default {
  name: "App",

  components: {
    TicTacToe,
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
