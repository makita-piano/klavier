<template>
  <div id="spotlight">
    <div id="center">
      <div id="logo">
        <h1 id="title">Klavier Page</h1>
      </div>
    </div>
    <footer>
      <p>© {{ new Date().getFullYear() }} Klavier Page</p>
    </footer>
  </div>
</template>

<style>
html {
  background: #494F5C;
  letter-spacing: .06em;
  line-height: 1.6;
}

body {
  color: #E8EEF2;
  font-family: trebuchet ms,Verdana,verdana ref,segoe ui,Candara,lucida grande,lucida sans unicode,lucida sans,Tahoma,sans-serif;
  margin: 0;
}

a {
  color: #E8EEF2;
}

#spotlight {
  align-items: center;
  display: flex;
  flex-direction: column;
  font-size: 1.5rem;
  justify-content: center;
  margin: auto;
  max-width: 93%;
  min-height: 100vh;
}

#center {
  display: flex;
  flex-direction: column;
  flex-grow: 1;
  justify-content: center;
}

#logo {
  margin: 3rem 0;
}

#title {
  margin: 0;
  text-align: center;
}

#social {
  font-size: 3rem;
  margin-left: 1rem;
  opacity: .8;
  text-align: center;
}

#twitter {
  display: inline-block;
  height: 1em;
  vertical-align: -.125em;
  width: 1em;
}

#wrapper {
  position: relative;
  width: 100%;
}

#wrapper:before {
  content: '';
  display: block;
  padding-top: 75%; /* 高さを幅の75%に固定 */
}

#namecard {
  border: 1px solid #DDD;
  border-radius: 5px;
  bottom: 0;
  box-shadow: 0 2px 5px #CCC;
  font-size: 1rem;
  left: 0;
  position: absolute;
  right: 0;
  top: 0;
}

#namecard-img {
  text-align: center;
}

#me-img {
  border-radius: 3rem;
  margin-top: .5rem;
}

#namecard-txt {
  margin: 1rem .5rem;
  text-align: center;
}

footer {
  font-size: .6em;
  line-height: normal;
  text-align: center;
}

</style>
