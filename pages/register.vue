<template>
  <div class="">
    <h1 class="text-4xl text-center mb-6">Bienvenue sur ton campus !</h1>
    <ul class="space-y-2 text-lg mb-6">
      <li>
        <label class="flex items-center">
          <input
            v-model="isAtLeastTwo"
            type="checkbox"
            class="form-checkbox h-6 w-6 mr-2"
          />
          Vous êtes au moins 2 ?
        </label>
      </li>
      <li>
        <label class="flex items-center">
          <input
            v-model="isProjectDefined"
            type="checkbox"
            class="form-checkbox h-6 w-6 mr-2"
          />
          Vous avez un projet stylé ?
        </label>
      </li>
      <li>
        <label class="flex items-center">
          <input
            v-model="isWhishesToChangeTheWorld"
            type="checkbox"
            class="form-checkbox h-6 w-6 mr-2"
          />
          Vous avez envie de changer votre monde ?
        </label>
      </li>
    </ul>
    <nuxt-link
      to="/step1"
      class="bg-blue-500 hover:bg-blue-600 transition p-5 px-10 rounded-md text-white text-lg disabled:bg-gray-500 block text-center"
      disabled="true"
    >
      Ok, let's go
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

<style scoped>
#__layout {
  background: none;
}
</style>
