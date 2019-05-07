<template>
  <Avatar />
</template>

<script>
import Avatar from './components/Avatar.vue';

export default {
  name: 'app',
  components: {
    Avatar
  }
}
</script>

<style lang="scss">
@import "~bulma/sass/utilities/_all";
@import "styles/_variables.scss";
</style>
