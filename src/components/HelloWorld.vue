<script setup>
import Modal from './Modal.vue'

defineProps({
  msg: String,
})
</script>

<template>
  <h1>Hello, {{ msg }}!</h1>

  <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
    Launch demo modal
  </button>

  <Modal />
</template>