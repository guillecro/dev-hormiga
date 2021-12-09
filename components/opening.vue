<template>
  <div
    class="
      h-screen
      container-fluid
      bg-head-dark
      flex flex-row
      mix-rounded
      scale-75
    "
  >
    <div class="container mx-auto flex flex-col justify-center">
      <h1
        v-anime="desplazarx"
        class="
          title-dev
          letter
          staggering-grid-demo
          text-4xl
          flex flex-row
          sm:text-8xl
          font-black
          head-title
          my-10
          mx-auto
        "
      >
        Dev Hormiga
        <img src="~/assets/antmove.gif" class="absolute" alt="" />
      </h1>
      <p class="p1">
        PROBANDO
      </p>
      <p
        v-anime="translate"
        class="
          block
          font-mono
          w-3/3
          py-5
          text-2xl text-center
          animate-pulse
          duration-1000
          justigy-center
        "
      >
        proximamente...
      </p>
      <div class="social flex justify-center gap-4">
        <a href="https://github.com/devhormiga" target="_blank"
          ><i id="git" class="fab fa-github-alt"></i
        ></a>
        <a href="https://www.linkedin.com/in/diego-v-0070161a4/" target="_blank"
          ><i id="ld" class="fab fa-linkedin"></i
        ></a>
      </div>
    </div>
  </div>
</template>
<script>

export default {
  data: () => {
    return {
      desplazarx: {
          scale: [40,1],
          opacity: [0,1],
          translateZ: 0,
          easing: "easeOutExpo",
          duration: 1500,
          delay: (letter, i) => 70*i,
      },
      translate: {
        delay: 3000,
        translateY: 375,
        duration: 3300,
        opacity: 1, // Opacity values goes from 0 to 1
      },
      scale: [
        { value: 0.1, easing: "easeOutSine", duration: 500 },
        { value: 1, easing: "easeInOutQuad", duration: 1200 },
      ],
    };
  },
  methods: {},
};
</script>
<style scoped>

.bg-ant {
  /* background: #fff url(/assets/antmove.gif) center center/cover repeat content-box fixed; */
  background-image: url("assets/antmove.gif");
  background-position: center 55%;
  background-repeat: no-repeat;
  background-size: 10rem;
}

.head-title {
  font-family: "Luckiest Guy", cursive;
  letter-spacing: 8px;
  color: #f0a70b;
  /* text-shadow: 0px 0px 10px #F0A70B; */
}
/* .bg-head{
  background: #f79d00;   fallback for old browsers 
  background: -webkit-linear-gradient(to bottom, #2f7744, #f79d00);  /* Chrome 10-25, Safari 5.1-6 
  background: linear-gradient(to bottom, #2f7744, #f79d00); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ 

} */
.bg-head-dark {
  background-color: #171717;
}
.bg-head {
  background: linear-gradient(190deg, #2f7744, #f79d00, #2bb937, #050504);
  background-size: 800% 800%;

  -webkit-animation: gradient 0.5s ease infinite;
  animation: gradient 15s ease infinite;
}

/* switch styles */
.switch {
  display: block;
  widows: 10%;
  height: 20%;
}
#marco vector {
  fill: #fff;
}
.social {
  color: #fff;
  font-size: 5rem;
}
p {
  position: absolute;
  top: 0;
  left: 44%;
  opacity: 0;
}
.title-dev {
transform: translate(-250px);}

.title-dev .letter {
  display: inline-block;
  line-height: 1em;
}
</style>