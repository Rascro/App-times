<template>
  <header>
    <div class="menu-esquerdo">
      <span>Home</span>
      <span>|</span>
      <span>Jogadores</span>
      <span>|</span>
      <span>Time</span>
    </div>
    <div class="menu-direito">
      <span>Sair</span>
    </div>
  </header>
  <RouterView />
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Cormorant+Garamond&display=swap");

#app {
  max-width: 1280px;
  margin: 0 auto;
  height: 100vh;
  font-weight: normal;
}

* {
  font-family: "Cormorant Garamond", serif;
}

header,
footer {
  height: 10%;
  background-color: rgb(171, 76, 135);
  color: black;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  padding-left: 20px;

  justify-content: space-between;
}

main {
  height: 80%;
}

header span {
  padding: 0 20px;
}
</style>
