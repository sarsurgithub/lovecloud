<template>
    <section class="three">
      <div class='three-inside'>
        <div class='textthree'>
          <h1>Avenir</h1>
          <h2>Professionnel</h2>
          <p> blabla </p>
          <p> blablablabla</p>
        </div>
        <img class='avenir' src='@/assets/pictures/teamwork.png'/>
      </div>
    </section>
</template>

<style lang="scss" scoped>

  .three{
    position: relative;
    z-index: 13;
    clip-path: polygon(0 0, 100% calc(0% + 10vw), 100% 100%, 0 100%);
    margin-top: -10vw;
    background: #192974 url('../assets/pictures/petits-nuages.png') repeat  center;
  }
  /* Extra small devices (phones, 600px and down) */
  @media only screen and (max-width: 600px) {
  .three-inside {
    display:flex;
    flex-direction: column-reverse;
  }
  .three {
    background-size: 400px;
  }
  }
  /* Small devices (portrait tablets and large phones, 600px and up) */
  @media only screen and (min-width: 600px) {
    .three-inside {
      display:flex;
      flex-direction: column-reverse;
    }
    .three {
      background-size: 600px;
      padding-bottom: 20px;
    }
  }
    /* Medium devices (landscape tablets, 768px and up) */
  @media only screen and (min-width: 768px) {
    .three-inside {
      display: flex;
      justify-content: space-evenly;
      flex-direction: row;
    }
  }

</style>
