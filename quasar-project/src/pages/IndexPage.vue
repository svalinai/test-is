<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    >
    
    <q-btn label="Klikni me" color="primary" @click="handleClick" class="q-mt-md"/>
  </q-page>
</template>

<script setup>
defineOptions({
  name: 'IndexPage'
});


const handleClick = () => {
  console.log("Button clicked!");
};
</script>

<style scoped>
.q-btn {
  margin-top: 20px;
}
</style>
