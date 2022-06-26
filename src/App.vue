<template>
  <transition name="site-transition" mode="in-out">
    <component :is="currentSite" />
  </transition>
</template>

<script>
export default {
  name: 'App'
}
</script>
