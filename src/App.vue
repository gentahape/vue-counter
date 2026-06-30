<script setup>
import { ref } from 'vue'

const counter = ref(0)
</script>

<template>
  <main>
    <div>
      <h1>Counter</h1>
      <span id="value">{{ counter }}</span>
      <div>
        <button @click="counter--" id="decrease">-</button>
        <button @click="counter++" id="increase">+</button>
      </div>
    </div>
  </main>
</template>

<style scoped>
  main {
    text-align: center;
    background-color: #333333;
    padding: 20px;
    border-radius: 8px;
  }

  #value {
    font-size: 50px
  }

  button {
    font-size: 16px;
    margin: 0 5px;
    background-color: #5555;
    color: #fff;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    border-radius: 4px;
  }

  button:hover {
    background-color: #7777;
  }

  button:active {
    animation: pulse 0.5s linear;
  }

  @keyframes pulse {
    0% {
      transform: scale(1);
    }
    50% {
      transform: scale(1.1);
    }
    100% {
      transform: scale(1);
    }
  }
</style>