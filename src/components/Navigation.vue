<template>
  <nav class="nav-container">
    <div class="brand-items">
      <div class="left-items">
        <div class="brand-img">
          <img src="src/assets/logotransparent.png" alt="Logo">
        </div>
        <div class="brand-title">
          <h1>Kriska de Lange</h1>
        </div>
      </div>

      <div class="right-items">
        <ul v-bind:class="{ 'menu': true, 'active': showMenu }">
          <li><h4><a href="#">About</a></h4></li>
          <li><h4><a href="#">Projects</a></h4></li>
          <li><h4><a href="#">Contact</a></h4></li>
        </ul>
        <div class="hamburger" v-on:click="showMenu = !showMenu" v-bind:class="{ 'close': showMenu }">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      showMenu: false
    }
  }
}
</script>

<style>
.nav-container {
  width: 100%;
  height: 44px;
  margin-bottom: 10px;
}

.brand-items {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.left-items {
  display: flex;
  align-items: center;
}

.brand-img img {
  max-width: 100%;
  height: auto;
  max-height: 50px;
  margin-right: 20px;
}

.right-items {
  display: flex;
  align-items: center;
}

/* Default styles for the menu */
.menu {
  display: flex;
  justify-content: center;
  list-style: none;
  margin: 0;
  padding: 0;
}

.menu li {
  margin: 10px 20px;
}

.menu a {
  color: #000;
  text-decoration: none;
  border-bottom: 1px solid #000;
  padding-bottom: 1px;
}

.menu a:hover {
  color: #000;
  text-decoration: none;
  border-bottom: 2px solid #000;
  padding-bottom: 1px;
}

/* Styles for the hamburger menu */
.hamburger {
  display: none;
  cursor: pointer;
}

.hamburger span {
  display: block;
  width: 30px;
  height: 2px;
  margin-bottom: 5px;
  background-color: #000;
}

.hamburger.close span:nth-child(1) {
  transform: rotate(45deg) translate(5px, 5px);
}

.hamburger.close span:nth-child(2) {
  opacity: 0;
}

.hamburger.close span:nth-child(3) {
  transform: rotate(-45deg) translate(5px, -5px);
}


/* Media query for small devices */
@media (max-width: 768px) {
  .menu {
    display: none;
  }

  .menu.active {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    position: absolute;
    top: 100px;
    left: 0;
    height: 100vh;
    width: 100%;
    background-color: rgb(255, 240, 222, 0.28);
    padding: 20px;
    backdrop-filter: blur(30px); 
  }

  .hamburger {
    display: block;
  }
}
</style>
