<template>
    <header>
    <nav>
      <ul>
        <li><nuxt-link to="/bankAccount">Compte Bancaire</nuxt-link> </li>
        <li><nuxt-link to="/company">Entreprise</nuxt-link> </li>
        <li><nuxt-link to="/identity">Identité</nuxt-link> </li>

      </ul>
    </nav>
  </header>
</template>

<script>
export default {

}
</script>

<style>
nav {
overflow: hidden;
  position: relative;
  margin-bottom: 25px;
  padding-bottom: 25px;}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: row;
}

nav li a {
  text-decoration: none;
  float: left;
  padding: 5px;
  color: hsla(160, 100%, 37%, 1);
}


nav li a:hover {
  color: whitesmoke;
}

</style>