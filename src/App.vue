<template>
  <div className="card-wrapper">
    <div className="header--image">
      <img src="../src/assets/images/image-qr-code.png">
    </div>
    <div className="text-wrapper">
      <div className="title">
        Improve your front-end skills by building projects
      </div>
      <div className="description">
        Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {}
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

#app {
}

$lightGray: hsl(212, 45%, 89%);
$grayishBlue: hsl(220, 15%, 55%);
$darkBlue: hsl(218, 44%, 22%);

body {
  padding: 0;
  background: $lightGray;
  font-family: 'Outfit', sans-serif;
  justify-content: center;
  display: flex;
  align-items: center;
}

.card-wrapper {
  margin: 10em 0;
  font-size: 1rem;
  padding: 0.8em;
  border-radius: 1em;
  background: white;
  width: 26ch;


}

.header--image {
  img {
    width: 26ch;
    border-radius: 0.7em;
  }
}

.text-wrapper {
  text-align: center;

  .title {
    font-weight: 700;
    font-size: 1.4rem;
    margin: 1em 0;
    color: $darkBlue;
  }

  .description {
    font-size: 1rem;
    margin-bottom: 2em;
    color: $grayishBlue;
  }
}
</style>
