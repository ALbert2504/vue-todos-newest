<template>
  <div class="about">
    <div class="container">
      <div class="about-content">
        <h1>This is an about page</h1>
        <p>
          This app has been created by me Albert Arakelyan with
          <a href="https://www.youtube.com/watch?v=KTFH4P8unUQ" target="_blank">Vue 3 crach course</a>
          made by <a href="https://www.youtube.com/@JohnKomarnicki" target="_blank">John Komarnicki</a>
          for being up to date with Vue 3, Vite and refreshing my knowledge and leraning
          Composition Api fully.
        </p>
        <h2>Special thanks to this the creator of this content!</h2>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.about {
  padding: 40px 12px 0;
  display: flex;
  justify-content: center;
  align-items: center;
}
.about-content {
  max-width: 600px;

  h1, h2, p {
    text-align: center;
  }
  p {
    margin: 16px 0 8px;
  }
}
</style>
