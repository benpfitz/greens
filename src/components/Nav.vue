<template>
  <div class="nav">
    <div class="logo">Greens to Your Door</div>
    <ul class="nav-links">
      <li>
        <a href="#">About</a>
      </li>
      <li>
        <a href="#">Products</a>
      </li>
      <li>
        <a href="#">FAQ</a>
      </li>
      <li>
        <a href="#">Checkout</a>
      </li>
    </ul>
    <div class="burger">
      <div class="line1"></div>
      <div class="line2"></div>
      <div class="line3"></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
  min-height: 8vh;
  background-color: #51b386;
  position: fixed;
  width: 100%;
  z-index: 10;
  box-shadow: 0 0 25px 0 black;
}
.nav a:hover {
  border-bottom: 3px solid whitesmoke;
}
.nav a:active {
  border-bottom: 3px solid whitesmoke;
}
.logo {
  color: rgb(224, 224, 224);
  text-transform: uppercase;
  letter-spacing: 6px;
  font-size: 40px;
  font-family: Arial, Helvetica, sans-serif;

  font-weight: bold;
}
.nav-links {
  display: flex;

  justify-content: space-around;
  width: 30%;
}
.nav-links li {
  list-style: none;
}
.nav-links a {
  color: rgb(224, 224, 224);
  text-decoration: none;
  letter-spacing: 3px;
  font-weight: bold;
  font-size: 16px;
  font-family: Arial, Helvetica, sans-serif;
}
.burger {
  display: none;
  cursor: pointer;
}
.burger div {
  width: 25px;
  height: 3px;
  background-color: rgb(224, 224, 224);
  margin: 5px;
  transition: all 0.3s ease;
}

@media screen and (max-width: 1024px) {
  .nav-links {
    width: 60%;
  }
}

@media screen and (max-width: 768px) {
  body {
    overflow-x: hidden;
  }

  .nav-links {
    position: absolute;
    right: 0px;
    height: 92vh;
    top: 8vh;
    background-color: #51b386;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 50%;
    transform: translatex(100%);
    transition: transform 0.5s ease-in;
  }
  .nav-links li {
    opacity: 0;
  }
  .burger {
    display: block;
  }
}

.nav-active {
  transform: translatex(0%);
}

@keyframes navLinkFade {
  from {
    opacity: 0;
    transform: translateX(50px);
  }
  to {
    opacity: 1;
    transform: translateX(0px);
  }
}

.toggle .line1 {
  transform: rotate(-45deg) translate(-5px, 6px);
}
.toggle .line2 {
  opacity: 0;
}
.toggle .line3 {
  transform: rotate(45deg) translate(-5px, -6px);
}
</style>
