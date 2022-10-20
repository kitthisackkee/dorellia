<template>
  <div class="page-title">
    <h1> {{Page_title}} </h1>
  </div>
</template>

<script>
export default {
    props: ['Page_title']
}
</script>

<style lang="scss">
.page-title{
    font-size: 3.222em;
}
</style>