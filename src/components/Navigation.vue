<template>
  <nav>
    <div class="left-items">
      <div class="brand-img">
        <img src="src/assets/logotransparent.png" alt="Logo">
      </div>
      <div class="brand-title">
        <h1>Kriska de Lange</h1>
      </div>
    </div>
    <div class="right-items">
      <ul>
        <li><a href="#">About</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Component</a></li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navigation'
}
</script>

<style>
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 80px;
  background-color: rgba(255, 255, 255, 0);
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
  justify-content: space-between;
  align-items: center;
  background-color: rgba(255, 255, 255, 0);

}
/* 
.logo img {
  height: 50px;
} */

ul {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
}

li {
  margin: 0 10px;
}

a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
}
</style>
