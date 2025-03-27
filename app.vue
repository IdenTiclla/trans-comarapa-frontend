<template>
  <div>
    <h1>Hello world trans-comarapa</h1>
    <button @click="handleclickfunction">press meee</button>
    <h2>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quos.</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quos.</p>

    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>

<script setup>
const handleclickfunction = () => {
  console.log("hello world")
}
</script>
