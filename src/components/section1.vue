<template>
    <section class="one">
      <div class='one-inside'>
        <div class='textone'>
          <h1>Le Cloud Computing</h1>
          <h2>Qu'est-ce que c'est ?</h2>
          <p> blablablabla</p>
          <p> blablablabla</p>
        </div>
        <img class='cloud' src='@/assets/pictures/supercloud.png'/>
      </div>
    </section>
</template>

<style lang="scss" scoped>
  .one {
    padding-top: 50px;
    position: relative;
    z-index: 12;
    margin-bottom: -35vw;
    clip-path: polygon(0 0, 100% 0, 100% calc(100% - 35vw), 0% 100%);
    background: #192974 url('../assets/pictures/petits-nuages.png') repeat  center;

    .one-inside {
      padding-bottom: 10%;
    }
  }
  @media only screen and (max-width: 600px) {
    .one-inside {
      display: flex;
      flex-direction: column-reverse;
    }
    .one {
      background-size: 400px;
    }
  }
  @media only screen and (min-width: 600px) {
    .one-inside {
    display: flex;
    flex-direction: column-reverse;
    }
    .one {
      background-size: 600px;
    }
  }
  @media only screen and (min-width: 768px) {
    .one-inside {
      display: flex;
      justify-content: space-evenly;
      flex-direction: row;
      padding-bottom: 30%;
    }
  }
  @media only screen and (min-width: 992px) {
    .cloud {
      padding-bottom: 10%;
    }
  }
</style>
