<template>
  <div class="fixed d-flex content-center items-center">
    <Nuxt />
  </div>
</template>

<script>
    export default {
        head: {
            bodyAttrs: {
                class: "main-page"
            }
        }
    }
</script>

<style scoped>
    .fixed {
        width: 100%;
        height: 100%;
        position: fixed;
    }
</style>