<template>
  <div>
    <nav>
      <RouterLink to="/ApiData">Data</RouterLink>
      <br />
      <RouterLink to="/BarChart"> Data about Age </RouterLink>
      <br />
      <Routerlink to="/PieChart"> Data about Race </Routerlink>
    </nav>
    <RouterView />
  </div>
</template>

<style>
nav {
  text-align: center;
  border: 1.35px solid rgb(56, 55, 55);
  max-width: 365px;
  margin-top: 20px;
  margin-left: 30px;
}
</style>
