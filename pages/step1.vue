<template>
  <div class="">
    <nuxt-link
      to="/step2"
      class="bg-blue-500 hover:bg-blue-600 transition p-5 px-10 rounded-md text-white text-lg disabled:bg-gray-500 block text-center"
      disabled="true"
    >
      Je continue
    </nuxt-link>
  </div>
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
