<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/todomvc">Todomvc</router-link>
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  data () {
    return {

    }
  },
  methods: {

  }
}
</script>
