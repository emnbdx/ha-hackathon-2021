<template>
  <div id="container3">
    <nuxt-link
      to="/step3"
      class="bg-red-500 transition p-5 px-10 rounded-md text-white text-lg disabled:bg-gray-500 block text-center btn3"
      disabled="true"
    >
      Cool
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

<style>
#container3 {
  height: 900px;
  background: url(../static/background-register.png) no-repeat top center;
  background-size: 100%;
}

.btn3 {
  position: absolute;
  top: 662px;
  left: 864px;
  background: #fc6867;
  color: #ffffff;
  padding: 0 2.5rem;
}
</style>
