<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <HelloWorld msg="Holiday Plans" seen="true"/>
    <CompanyList class="contry-list"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import CompanyList from "./components/CompanyList";

export default {
  name: "App",
  components: {
    HelloWorld,
    CompanyList
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.contry-list {
  margin-top: 2rem;
}
</style>
