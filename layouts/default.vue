<template>
  <div>
    <nuxt/>
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  margin: 0;
}

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}

.button--purple {
position: relative;
background-color: #526488;
z-index: 1; 
border-radius: 2px;
border: none;
padding: 16px 20px;
margin-top: 8px;
font-family: Quicksand-Bold;
font-size: 1.3rem;
/* color: #E0DEF0; */
color: hsla(247, 38%, 91%, 0.5);
letter-spacing: 0.76px; 
transition: 0.6s ease;
}

.button--purple:hover {
  background-color: #697B9E;
  color: #FFF;
  cursor: pointer;
}

.circle-arrow {
  stroke-opacity: 0.5;
  transition: 0.6s ease;
}

.button--purple:hover .circle-arrow {
  stroke-opacity: 1;
}

</style>
