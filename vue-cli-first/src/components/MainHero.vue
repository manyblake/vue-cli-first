<template>
  <div class="hero">
    <div class="container">
      <h2 class="hero__title">E questo è il titolo dell'hero</h2>
      <picture>
        <img src="https://picsum.photos/800/400" />
      </picture>
    </div>
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.hero {
  background-color: bisque;
  padding: 24px;
}

.container {
  max-width: 800px;
  margin: 0 auto;
}

.hero__title {
  padding: 24px;
}
</style>
