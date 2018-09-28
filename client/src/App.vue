<template>
  <div id="app">
      <div class="col-lg-8">
        <router-view></router-view>
      </div>
    </div>
  </div>
</template>

<script>
import axios from "axios";

export default {
  name: 'App',
  data() {
    return {
    }
  }
}
</script>

<style>
</style>
