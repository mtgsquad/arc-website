<template>
  <div class="container">
    <div>
      <SmallLogo />
      <h1 class="title">About Us</h1>
      <p class="para">
        We are Arc, the team that created free Minecraft capes for all! But why?
        What's the point? Most people's childhood dream was to have a cool
        Minecraft cape, but they didn't have money to spend $10 on an OptiFine
        cape, $12 on a Lunar cape, $12 on a Badlion cape, or $10 on a PvPLounge
        cape.
      </p>
      <br />
      <a class="white" href="/">Go back home</a>
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
  font-size: 70px;
  color: #ededee;
  letter-spacing: 1px;
}

.para {
  font-weight: 300;
  font-size: 20px;
  color: #ededee;
  word-spacing: 1px;
  padding-bottom: 15px;
}

.white {
  color: #ededee;
}
</style>
