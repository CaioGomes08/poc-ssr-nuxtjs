<template>
  <div>
    <nav class="navbar">
      <ul>
        <nuxt-link class="item-nav" to="/">Home</nuxt-link>
        <nuxt-link class="item-nav" to="/about">About</nuxt-link>
      </ul>
    </nav>
    <Nuxt />
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.container {
  margin: 0 auto;
  max-width: 1200px;
  display: flex;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.navbar {
  background: white;
}

.navbar ul {
  display: flex;
  align-items: center;
  justify-content: center;
  list-style: none;
}

.item-nav {
  font-size: 20px;
  text-decoration: none;
  padding: 10px;
  transition: ease-in 0.5s;
  color: black;
}

.item-nav:hover {
  color: darkgreen;
}
</style>
