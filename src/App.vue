<template>
  <div id="app">

    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search...">
      </div>
    </main>

  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      api_key: 'f5d0f559efaf9e56722a8662af21b4c3'
    }

  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'monsterrat', sans-serif;
}

#app {
  background-image: url('./assets/cold-bg.jpg');
  background-size: contain;
  background-position: bottom;
  transition: 0.4s;
}

main {
  min-height: 100vh;
  padding: 25px;
  background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.25), rgba(0, 0, 0, 0.75));
}

.search-box .search-bar{
  display: block;
  width: 100%;
  padding: 15px;

  color: #313131;
  font-size: 20px;

  appearance: none;
  border: none;
  outline: none;

  box-shadow: 0,px 0px 8px rgba(0, 0, 0, 0.25);
  background-color: rgba(255, 255, 255, 0.5);
  border-radius: 0px 16px 0px 16px;
  transition: 0.4s;
}

.search-box .search-bar:focus {
  box-shadow: 0px 0px 16px rgba(0, 0, 0, 0.25);
  background-color: rgba(255, 255, 255, 0.57);
  border-radius: 16px 0px 16px 0px;

}
</style>
