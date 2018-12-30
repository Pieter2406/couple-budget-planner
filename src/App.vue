<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li class="nav-item">
            <img class="logo" src="./assets/logo.png">
          </li>
        </ul>
      </nav>
    </header>
    <main>
      <AccountsOverview msg="Welcome to Your Vue.js App"/>
    </main>
  </div>
</template>

<script>
import AccountsOverview from "./components/AccountsOverview.vue";

export default {
  name: "app",
  components: {
    AccountsOverview
  }
};
</script>

<style>
body {
  background: linear-gradient(to bottom, #555, #999);
  background-attachment: fixed;
}

main {
  margin: 0 auto;
  padding: 30 px;
  background-color: white;
  width: 1024px;
  min-height: 300px;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
