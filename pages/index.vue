<template>
  <nuxt-link
    to="/register"
    class="bg-red-500 hover:bg-red-600 transition p-5 px-10 rounded-md text-white text-lg disabled:bg-gray-500 block text-center"
    disabled="true"
  >
    C'est parti !
  </nuxt-link>
</template>

<script>
export default {
  data() {
    return {
      isAtLeastTwo: false,
      isProjectDefined: false,
      isWhishesToChangeTheWorld: false,
    }
  },
}
</script>
