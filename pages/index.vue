<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">Arc</h1>
      <h3 class="subtitle">Free Minecraft Capes</h3>
      <div class="links">
        <a
          href="https://dsc.gg/arc"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          Discord
        </a>
        <a
          href="https://github.com/ArcCapes"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
        <a href="/about" target="" rel="noreferrer" class="button--grey">
          About Us
        </a>
        <a href="/install" target="" rel="noreferrer" class="button--grey">
          Installation
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
* {
  background-color: hsl(240, 10%, 6%);
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 74px;
  color: #ededee;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 36px;
  color: #ededee;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.links a {
  color: #ededee;
}
</style>
