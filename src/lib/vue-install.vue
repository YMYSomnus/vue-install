<template>
  <div class="vue-install">
    <div> {{title}}
    </div>
  </div>
</template>
<script>
  export default {
    name: 'vue-install',
    props: {
      title: {
        type: String
      }
    }
  }
</script>

<style>
  .vue-install {
    width: 200px;
    height: 100px;
  }
</style>
