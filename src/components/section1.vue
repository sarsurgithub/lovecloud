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
    padding-top: 15%;
    position: relative;
    z-index: 12;
    margin-bottom: -35vw;
    clip-path: polygon(0 0, 100% 0, 100% calc(100% - 35vw), 0% 100%);
    background-color: #192974;

    .one-inside {
      padding-bottom: 10%;
    }
  }
  @media only screen and (max-width: 600px) {
    .one-inside {
      display: flex;
      flex-direction: column-reverse;
    }
  }
  @media only screen and (min-width: 600px) {
    .one-inside {
    display: flex;
    flex-direction: column-reverse;
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
    .one-inside {
      display: flex;
      justify-content: space-evenly;
      padding-bottom: 30%;
      }
    .cloud {
      padding-bottom: 10%;
    }
  }
  @media only screen and (min-width: 1200px){
    .one-inside {
      display: flex;
      justify-content: space-evenly;
      padding-bottom: 30%;
    }
  }
</style>
