<script setup>
import { vConfetti } from "@neoconfetti/vue";
</script>

<template>
  <span v-confetti />
  <div class="win-message">Yay! You have won the game! Will you be my girlfriend? 🎉</div>
  <img src="@/assets/pic.jpg" alt="celebration" class="win-image" />
</template>

<style scoped>
.win-message {
  font-size: 14px;
  margin: 10px 0;
  color: #ff5afa;
}
.win-image {
  width: 500px;   /* change this number to make it smaller or larger */
  border-radius: 12px;
  margin: 10px 0;
}
</style>
