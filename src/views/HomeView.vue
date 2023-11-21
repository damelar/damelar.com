<script setup>
</script>

<template>
  <main>
    <img alt="Vue logo" class="logo" width="300" src="@/assets/gandalfMac.jpeg"/>
  </main>
  <p>
    &bull; Programador.
    <br>
    &bull; Principais Tecnologias: <clr>.NET</clr>, <clr>Go</clr> e <clr>VueJS</clr>.
    <br>
    &bull; Interessado em um pouco de tudo.
  </p>
</template>

<style scoped>

clr {
    color: hsla(160, 100%, 37%, 1);
}

main {
  text-align: center;
}

img {
  max-width: 70%;
  margin: 0 auto;
  margin-top: 20px;
  place-items: center;
  display: grid;
}

@media only screen and (max-width: 1024px) {
 img{
   max-width: 80%;
   max-height: 600px;
  margin-top: 30px;
 } 
}
</style>