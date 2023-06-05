<template>
  <h2>Nama : {{ nama }}</h2>
  <button v-on:click="changeName">Change Name</button>
</template>

<script>

export default {
  name: "App",
  data() {
    return {
      nama: "sausan",
    };
  },
  methods: {
    changeName() {
      this.nama = "joko";
      this.nama = "putra";
      this.nama = "manik";
    },
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
