<template>
  <nav class="bg-2 grid-rows-1 flex align-center">
    <div class="logo flex align-center justify-center m-2">
      <img width="50" src="/images/shiba.png" />
      <p class="text-5"><a href="/">Doggo land</a></p>
    </div>
    <div class="mx-5 my-4 flex align-center justify-center">
      <p class="aL text-4 flex justify-center align-center"><a href="/memes">Memes</a></p>
    </div>
  </nav>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Serif+Display:wght@500&display=swap');
nav {
  height: 4rem;
}
.logo > p{
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 25px;
  font-family: 'Noto Serif Display', serif;
}
.aL {
  font-size: 20px;
  font-family: "DM Serif Display";
}
</style>
