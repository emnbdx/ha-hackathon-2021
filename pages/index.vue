<template>
  <div id="container">
    <nuxt-link
      to="/register"
      class="bg-white-500 transition p-5 px-10 rounded-md text-red text-lg disabled:bg-gray-500 block text-center btn1"
      disabled="true"
    >
      C'est parti !
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
#container {
  height: 3410px;
  background: url(../static/background.png) no-repeat top center;
  background-size: 100%;
}

.btn1 {
  position: absolute;
  top: 556px;
  left: 708px;
  background: white;
  color: #fc6867;
  height: 63px;
}
</style>
