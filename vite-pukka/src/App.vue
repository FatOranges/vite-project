<script setup>
import LinkList from "./components/LinkList.vue";
</script>

<template>
  <LinkList/>
</template>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: linear-gradient(45deg, #fbda61, #ff5acd);
  }
</style>
