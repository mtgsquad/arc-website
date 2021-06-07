<template>
  <div class="container">
    <div>
      <SmallLogo />
      <h1 class="title">Installation</h1>
      <p class="para">
        <b>Windows:</b>
        <br />
        1. Download And Run The Installer (<a
          href="https://cdn.discordapp.com/attachments/832406713838862346/832406952067334204/ArcInstaller.msi"
          target="_blank"
          >Download</a
        >)
        <br />
        2. Install the program normally
        <br />
        3. Launch the newly installed application
        <br />
        4. If it prompts you to download Dotnet, press "Yes" and install it
        <br />
        5. Reopen the program, and press "Install Arc" (If it says "Installation
        failed", restart your PC and try again)
        <br />
        6. Done! The next time you run Minecraft, you will see your cape.
        <br />
        <br />
        <b>Linux / macOS:</b>
        <br />
        1. Hold Ctrl+Alt+T and a terminal window will come up. (If it doesn't,
        open the terminal another way)
        <br />
        2. Type <code>sudo nano /etc/hosts</code>, click "enter", then type in
        your password.
        <br />
        3. Press the down arrow key until you are at the bottom of the file.
        <b
          >NOTE: Do NOT touch the original contents of the file! Just follow the
          directions carefully!</b
        >
        <br />
        4. Type in <b>35.231.77.253</b>, click "tab", then type in
        <b>s.optifine.net</b>
        <br />
        5. Hold "control" (not command) and "x" at the same time.
        <br />
        6. Press "y", then click "enter". You can then close out the window.
        <br />
        7. Done! The next time you run Minecraft, you will see your cape.
      </p>
      <br />
      <a class="white" href="/">Go back home</a>
      <br />
      <br />
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
