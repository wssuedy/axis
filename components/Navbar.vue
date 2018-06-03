<template lang="html">

  <nav class="navbar">
    <nuxt-link :to="{path:'/mystoretest'}">go mystoretest page</nuxt-link>

    <nuxt-link :to="{path:'/test'}">go test page</nuxt-link>
    <nuxt-link :to="{path:'/abc'}">go abc page</nuxt-link>
    <nuxt-link :to="{path:'/sub/a'}">go a page</nuxt-link>
    <nuxt-link :to="{path:'/sub/b'}">go b page</nuxt-link>
    <nuxt-link :to="{path:'/sub/about'}">go sub about page</nuxt-link>

  </nav>

</template>

<script>

export default {
}
</script>

<style lang="css">

.navbar{
  min-height: 5px;
}
.navbar >a{
  padding:10px;
  margin:5px;
  border:1px solid #333;
}
</style>
