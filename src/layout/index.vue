<template>
    <div>
        <Header></Header>
        <Content></Content>
    </div>
  </template>
  
  <script setup lang="ts">
  import {ref,reactive} from 'vue'
  import Header from './header/index.vue'
  import Content from './content/index.vue'
  </script>
  
  <style lang="less" scoped>
  
  </style>