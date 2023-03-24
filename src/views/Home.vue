<template>
  <div>
    <RouterLink class="link" to="/todo">Todo app</RouterLink>
    <RouterLink class="link" to="/miniapp">Mini App</RouterLink>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Oswald:wght@600&display=swap');
div {
  background-image: radial-gradient( circle 610px at 5.2% 51.6%,  rgba(5,8,114,1) 0%, rgba(7,3,53,1) 97.5% );
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 60px;
}

.link {
  font-family: 'Oswald', sans-serif;
  text-decoration: none;
  font-size: 50px;
  color: #fff;
}
</style>
