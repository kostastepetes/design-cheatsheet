<template>
  <slot />
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
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

.button--green {
  display: inline-block;
  margin: 0.25em;
  border-radius: 4px;
  border: 2px solid #FE5F55;
  color: black;
  text-decoration: none;
  padding: 10px 30px;
  cursor:pointer;
}

.button--green:hover {
  color: black;
  background-color: #FE5F55;
}

.button--grey {
  display: inline-block;
  margin: 0.25em;
  border-radius: 4px;
  border: 2px solid #09488b;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
  cursor:pointer;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  max-width: 90%;
  padding: 4em 0.5em;
  display: block;
  text-align: center;
}

.logo {
  max-width: 100%;
  padding: 0.5em;
  border-radius: 35px;
}

.nav a {
  color: black !important;
}

.links {
  padding: 1em 0 1.5em 0;
}

.posts {
  margin: 1em;
  text-align: left;
}

.container h2 {
  margin-top: 1.5em;
  color: black !important;
}

.container ul {
  margin: 1em auto;
  list-style: none;
}

.container p {
  margin: 1em 0;
  text-align: justify;
}

.container a {
  max-width: 75%;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

footer {
  position: fixed;
    bottom: 0;
    left: 0;
    right: 0;
    text-align: center;
    background-color: #bfb1b1;
    color: #fff;
    padding: 10px;
}
</style>
