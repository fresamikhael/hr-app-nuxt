<template>
  <div>
    <div><h1>My blog navigation bar here</h1></div>
    <Nuxt />
  </div>
</template>

<script>
export default {
  layout: 'blog',
  // OR
  layout(context) {
    return 'blog'
  },
}
</script>
