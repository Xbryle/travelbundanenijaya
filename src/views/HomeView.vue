<template>
  <div class="hero">
    <!-- <HomePageProto/> -->
    <!-- <HomePage /> -->
    <HomePageProto2 />
    <AboutPageProto />
    <HelpPage />
    <!-- <AboutPage /> -->
    <!-- <div class="new" id="new">
      <div class="triangle">
          <a href="#about">
              <i class="down fa-solid fa-angles-down"></i>
          </a>
      </div>
    </div> -->
    <!-- <AboutServices id="aboutServices" /> -->
    <Ask />
    <Map />
    <!-- <Join /> -->
    <FooterPage />
  </div>
</template>

<script>
  // import HomePage from './pages/homePage.vue';
  // import HomePageProto from './pages/homePageProto.vue';
  import HomePageProto2 from './pages/homePageProto2.vue';
  // import AboutPage from './pages/aboutPage.vue';
  import AboutPageProto from './pages/aboutPageProto.vue';
  // import AboutServices from './pages/about-our-services-proto.vue';
  import Ask from './pages/askPage.vue';
  import Map from './pages/mapPage.vue';
  // import Join from './pages/joinPage.vue';
  import FooterPage from './pages/footerPage.vue';
  import HelpPage from './pages/helpPage.vue';

  export default {
    name: 'HomeView',

    components: {
      // HomePage,
      HomePageProto2,
      // AboutPage,
      AboutPageProto,
      // AboutServices, 
      Ask,
      Map,
      // Join,
      FooterPage,
      // HomePageProto,
      HelpPage,
    },
  }
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Oswald:wght@200..700&display=swap');

body {
  font-family: 'Poppins', sans-serif;
  background-image: linear-gradient(to right, #10131D,#151927,#1F2334,#10131D);
  background-repeat: no-repeat;
  background-attachment: fixed;
}

.v-toolbar__content, .v-toolbar__extension {
  padding: 0;
}

/* .nav-link {
  text-decoration: none;
  font-weight: 500;
}

.new {
  position: relative;
  display: flex;
  justify-content: center;
}
.new .triangle {
  z-index: 2;
  position: absolute;
  width: 4em;
  height: 4em;
  background-color: #ffffff;
  top: -32px;
  transform: rotate(45deg);
  display: grid;
  align-items: center;
  justify-content: center;
  cursor: pointer;
}
.new .down {
  color: #000;
  transform: rotate(-225deg);
  position: relative;
  left: -12px;
  top: -12px;
  transition: all .3s ease-out;
  z-index: 3;
}
.new:hover .down {
  transform: rotate(-45deg);
} */


.hero {
    width: 100%;
    height: max-content;
    display: grid;
    justify-items: center;
    position: relative;
    justify-content: center;
}
</style>
