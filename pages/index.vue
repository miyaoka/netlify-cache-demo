<template>
  <div>
    <h1>Cache test</h1>

    <div class="font1">フォント1</div>
    <div class="font2">フォント2</div>

    <img src="/img1.jpg" width="500">
    <img src="/img2.jpg" width="500">

    <div>
      Photo:
      <a href="https://www.nasa.gov/content/goddard/hubble-s-high-definition-panoramic-view-of-the-andromeda-galaxy" target="_blank">Hubble's High-Definition Panoramic View of the Andromeda</a>
    </div>
  </div>
</template>

<style scoped>
@font-face {
  font-family: 'font1';
  src: url(/font/font1.woff) format('woff');
  font-display: swap;
}
@font-face {
  font-family: 'font2';
  src: url(/font/font2.woff) format('woff');
  font-display: swap;
}
.font1 {
  font-family: 'font1';
  font-size: 3rem;
}
.font2 {
  font-family: 'font2';
  font-size: 3rem;
}
</style>

