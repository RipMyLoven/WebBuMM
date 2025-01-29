<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />

    <div>
      <p>None</p>
    </div>
  </div>
</template>

<script setup>
const { data } = await useFetch("http://localhost:3001/api/hello");
console.log(data.value);

</script>