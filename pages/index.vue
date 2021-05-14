<template>
  <div>
    <button @click="toast">toast me!</button>
  </div>
</template>

<script>
import Toast from 'toastr'

export default {
  methods: {
    toast() {
      Toast.warning('My name is Inigo Montoya. You killed my father, prepare to die!')
    },
  },
}
</script>

<style>
@import "toastr";
</style>
