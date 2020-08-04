<template>
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
</template>

<style lang="scss" scoped>

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
  @media only screen and (min-width: 768px) {
    .heig {
      padding-top: 20%;
    }
    .two-inside {
      display: flex;
      justify-content: space-evenly;
    }
  }
  @media only screen and (min-width: 992px) {
    .heig {
      padding-top: 20%;
    }
    .two-inside {
      display: flex;
      justify-content: space-evenly;
    }
  }
  @media only screen and (min-width: 1200px){
    .heig {
      padding-top: 20%;
    }
    .two-inside {
      display: flex;
      justify-content: space-evenly;
    }
  }
</style>
