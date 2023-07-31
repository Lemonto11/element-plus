<template>
  <el-switch
    v-model="value1"
    class="mb-2"
    active-text="Pay by month"
    style="color:#434343"
  
  />
  <br />
 
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const value1 = ref(true)
const value2 = ref(true)
const value3 = ref(true)
const value4 = ref(true)
const value5 = ref(true)
const value6 = ref(true)
</script>
