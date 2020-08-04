<template>
  <div class='page'>
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
    <section class="two">
      <div class='two-inside'>
        <img class='heig' src='@/assets/pictures/heigorange.png'/>
        <div class='texttwo'>
          <h1>Comment se former</h1>
          <h2>aux technologies du web ?</h2>
          <p> blabla </p>
          <p> blablablabla</p>
        </div>
      </div>
    </section>
    <div class=wrap>
      <section class='minisection'/>
    </div>
    <section class="three">
      <div class='three-inside'>
        <div class='textthree'>
          <h1>Avenir</h1>
          <h2>Professionnel</h2>
          <p> blabla </p>
          <p> blablablabla</p>
        </div>
        <img class='avenir' src='@/assets/pictures/App.png'/>
      </div>
    </section>
  </div>
</template>

<style lang="scss" scoped>
  /* general */
  .page {
    color: lightgray;
  }
  h1 {
      font-size: 36px;
      margin-right: 5%;
      margin: 10px;
      color:white;
    }
    h2 {
      font-size: 24px;
      margin-left: 20%;
      font-weight: normal;
      margin: 10px;
      color: #65BAEF;
    }
    p {
      font-size: 16px;
      padding-left:50px;
      max-width: 500px;
      text-align: left;
      color: #D3DCE4;
    }
    img {
      max-width: 280px;
      align-self: center;
      padding: 20px;
    }
    section {
    padding: 20vh 0;
  }
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

  .two {
    position: relative;
    z-index: 11;
    background-color: #F4F5FF;
    .two-inside {

      .texttwo {
        padding-top: 5%;
        h1 {
          color:#192974;
        }
        h2 {
          color: #65BAEF;
        }
        p {
          color: #5C6975;
        }
      }
    }
  }
  .minisection {
    padding: 10vh 0;
    position: relative;
    z-index: 12;
    clip-path: polygon(0 0, 100% calc(0% + 10vw), 100% 100%, 0 100%);
    margin-top: -10vw;
    background-color: #1C90E6;
  }
  .three{
    position: relative;
    z-index: 13;
    clip-path: polygon(0 0, 100% calc(0% + 10vw), 100% 100%, 0 100%);
    margin-top: -10vw;
    background-color: #192974;
  }

    /* Extra small devices (phones, 600px and down) */
  @media only screen and (max-width: 600px) {
  .one-inside {
    display: flex;
    flex-direction: column-reverse;
  }
  .three-inside {
    display:flex;
    flex-direction: column-reverse;
  }
  }

  /* Small devices (portrait tablets and large phones, 600px and up) */
  @media only screen and (min-width: 600px) {
    .one-inside {
    display: flex;
    flex-direction: column-reverse;
  }
  .three-inside {
    display:flex;
    flex-direction: column-reverse;
  }
  p {
    margin-left: 20%;
  }
  img {
    /*max-width: 400px;*/
    padding-bottom: 10%
  }
  }

  /* Medium devices (landscape tablets, 768px and up) */
  @media only screen and (min-width: 768px) {
  img {
    max-width: 350px;
  }
  .one-inside {
    display: flex;
    justify-content: space-evenly;
    flex-direction: row;
    padding-bottom: 30%;
    }
  .heig {
    padding-top: 20%;
  }
  .two-inside {
    display: flex;
    justify-content: space-evenly;
  }
  .minisection {
    padding: 8vh 0;
  }
  .three-inside {
    display: flex;
    justify-content: space-evenly;
    flex-direction: row;
  }
  }

  /* Large devices (laptops/desktops, 992px and up) */
  @media only screen and (min-width: 992px) {
  h1 {
    font-size:40px;
  }
  h2 {
    font-size: 32px;
  }
  p {
    font-size: 24px;
  }
  img {
    max-width: 400px;
  }
  .one-inside {
    display: flex;
    justify-content: space-evenly;
    padding-bottom: 30%;
    }
  .heig {
    padding-top: 20%;
  }
  .cloud {
    padding-bottom: 10%;
  }
  .two-inside {
    display: flex;
    justify-content: space-evenly;
  }
  .minisection {
    padding: 8vh 0;
  }
  .three-inside {
    display: flex;
    justify-content: space-evenly;
  }
  }

  @media only screen and (min-width: 1200px){
  section {
    padding: 40vh 0;
  }
  h1 {
    font-size:40px;
  }
  h2 {
    font-size: 32px;
  }
  p {
    font-size: 24px;
  }
  img {
    max-width: 700px;
  }
  .one-inside {
    display: flex;
    justify-content: space-evenly;
    padding-bottom: 30%;
    }
  .heig {
    padding-top: 20%;
  }
  .two-inside {
    display: flex;
    justify-content: space-evenly;
  }
  .minisection {
    padding: 18vh 0;
  }
  .three-inside {
    display: flex;
    justify-content: space-evenly;
  }
}

</style>
