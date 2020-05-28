<template>
  <div id="app">
    <board />
  </div>
</template>

<script>
// インポートするファイル
import Board from "./components/Board.vue";

export default {
  name: "App",
  components: {
    Board
  }
};
</script>

