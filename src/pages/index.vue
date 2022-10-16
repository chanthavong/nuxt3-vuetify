<template>
  <div>
    <v-container fluid>
      <v-btn variant="flat" color="primary" @click="sayHi" class="mb-4"
        >Click me</v-btn
      >
      <v-alert type="success">I'm a success alert.</v-alert>

      <br />

      <v-alert type="info">I'm an info alert.</v-alert>

      <br />

      <v-alert type="warning">I'm a warning alert.</v-alert>

      <br />

      <v-alert type="error">I'm an error alert.</v-alert>
    </v-container>
  </div>
</template>

<script setup lang="ts">
const sayHi = () => alert("Hello world");
</script>
