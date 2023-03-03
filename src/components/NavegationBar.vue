<template>
  <div class="navbar">
    <p class="navbar__logo"><strong>Github</strong> <i>Search</i></p>
    <ul class="navbar__navegation">
      <li>início</li>
      <li>favoritos</li>
    </ul>
  </div>
</template>

<script>

export default {
  name: 'NavegationBar'
}

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter&display=swap');

* {
  box-sizing: border-box;
  list-style: none;
  margin: 0;
  padding: 0;
}

.navbar {
  background-color: #D9D9D9;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  height: 84px;
  padding: 20px;
  font-family: 'Inter', sans-serif;
  font-weight: 500;

  display: flex;
  justify-content: space-between;
}

.navbar__logo {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-size: 32px;
  line-height: 39px;
  display: flex;
  align-items: center;
  text-align: center;
}

strong {
  margin-right: 10px;
}

.navbar__logo i {
  font-style: italic;
}

.navbar__navegation {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 700;
  font-size: 20px;
  line-height: 24px;
  display: flex;
  align-items: center;
  text-align: center;
  text-transform: uppercase;
}

ul li {
  padding: 10px;
}

</style>