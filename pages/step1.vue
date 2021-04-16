<template>
  <div id="container2">
    <nuxt-link
      to="/step2"
      class="bg-blue-500 transition p-5 px-10 rounded-md text-white text-lg disabled:bg-gray-500 block text-center btn2"
      disabled="true"
    >
      Ça me va
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
#container2 {
  height: 1747px;
  background: url(../static/background-step1.png) no-repeat top center;
  background-size: 100%;
}

.btn2 {
  position: absolute;
  top: 1591px;
  left: 400px;
  background: #fc6867;
  color: #ffffff;
  padding: 0 2rem;
}
</style>
