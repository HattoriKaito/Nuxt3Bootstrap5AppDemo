<template>
  <div>
    <header>
      <h1>Apex Legends Guide</h1>
      <nav>
        <nuxt-link to="/">Home</nuxt-link>
        <nuxt-link to="/rank-tips">Ranking Tips</nuxt-link>
      </nav>
    </header>
    <main>
      <nuxt />
    </main>
  </div>
</template>

<style scoped>
/* Add styles for the layout */
header {
  background-color: #333;
  color: white;
  padding: 1rem;
  text-align: center;
}

nav {
  margin-top: 1rem;
}

nav a {
  color: white;
  margin-right: 1rem;
  text-decoration: none;
}
</style>
