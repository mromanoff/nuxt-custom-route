<template>
  <div>
    <div class="nav">
      <nuxt-link to="/">Home</nuxt-link> |
      <nuxt-link to="/blah">404</nuxt-link> |
      <nuxt-link to="/category">Category</nuxt-link> |
      <nuxt-link to="/directory">Directory</nuxt-link>
    </div>

    <p>&nbsp;</p>

    <div class="nav">
      <p>Aliases using category page</p>
      <p>&nbsp;</p>
      <nuxt-link to="/suv">Suv</nuxt-link> |
      <nuxt-link to="/sedan">Sedan</nuxt-link> |
      <nuxt-link to="/sport">Sport</nuxt-link>
    </div>

    <p>&nbsp;</p>

    <div class="nav">
      <p>Aliases using directory page</p>
      <p>&nbsp;</p>
      <nuxt-link to="/acura">Acura</nuxt-link> |
      <nuxt-link to="/bmw">BMW</nuxt-link> |
      <nuxt-link to="/ford">Ford</nuxt-link>
    </div>
    <nuxt />
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
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
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

.nav {
  margin: 1rem auto;
  text-align: center;
}
</style>
