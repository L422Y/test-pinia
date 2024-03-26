<template>
  <div>
    {{testStore.count}}
    <button @click="testStore.increment">
      Increment
    </button>
    <button @click="testStore.decrement">
      Decrement
    </button>
  </div>
</template>
<script lang="ts" setup>
import { useTestStore } from "~/stores/test"

const testStore = useTestStore()

</script>
