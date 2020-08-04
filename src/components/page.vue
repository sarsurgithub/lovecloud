<template>
  <div class='page'>
    <section1/>
    <section2/>
    <section class='minisection'/>
    <section3/>
  </div>
</template>

<script>
import section1 from '@/components/section1.vue';
import section2 from '@/components/section2.vue';
import section3 from '@/components/section3.vue';

export default {
  components: {
    section1,
    section2,
    section3,
  },
};
</script>
<style lang="scss">
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
  .minisection {
    padding: 10vh 0;
    position: relative;
    z-index: 12;
    clip-path: polygon(0 0, 100% calc(0% + 10vw), 100% 100%, 0 100%);
    margin-top: -10vw;
    background-color: #1C90E6;
  }

  /* Small devices (portrait tablets and large phones, 600px and up) */
  @media only screen and (min-width: 600px) {
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
    .minisection {
      padding: 8vh 0;
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
  .minisection {
    padding: 8vh 0;
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
  .minisection {
    padding: 18vh 0;
  }
}

</style>
