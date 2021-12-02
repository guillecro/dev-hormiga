<template>
  <div class="container-fluid bg-head-dark	 h-5/6  flex flex-row mix-rounded scale-75">
    <div class="container rounded-full  border-8 border-yellow-600 border-opacity-50 shadow-2xl bg-transparent mx-auto w-1/3 ">
      <img class="object-fill object-center " src="~/assets/hormiga.png" />
    </div>
    <div class="flex flex-col">
        <h1 class="text-8xl font-black head-title my-10">Dev<br>Hormiga</h1>
        <p class="font-mono w-2/3 py-5 text-2xl text-center">
            Desarrollo de pequeñas soluciones para tus proyectos
            <a href="https://github.com/devhormiga">GitHub</a>
        </p>
    </div>
    <div class="m-10" >
      <!-- <img src="~/assets/swicht.svg" alt=""> -->
      <svg id="iswi" class="switch"  viewBox="0 0 160 228" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g id="swicht">
              <g id="Group">
                  <g id="Group_2">
                      <g id="marco">
                          <path id="Vector" d="M132 0.666687H28C12.6667 0.666687 0.333336 13 0.333336 28.3334V199.667C0.333336 215 12.6667 227.333 28 227.333H132.333C147.667 227.333 160 215 160 199.667V28.3334C160 13 147.333 0.666687 132 0.666687ZM153.333 199.667C153.333 211.333 144 220.667 132.333 220.667H28C16.3333 220.667 7 211.333 7 199.667V28.3334C7 16.6667 16.3333 7.33335 28 7.33335H132.333C144 7.33335 153.333 16.6667 153.333 28.3334V199.667Z" fill="black" />
                      </g>
                      <g id="ficha1">
                          <path id="Vector_2" d="M118 59.3333C117.333 57.3333 115.667 56.3333 113.333 56.3333C113.333 56.3333 75.6667 56 75 56.3333C75 56.3333 75 56.3333 74.6667 56.3333C73 57 72 58.6667 72.3333 60.3333L71.6667 61.3333H63C61 61.3333 59 63 59 65.3333V154C59 156 60.6667 158 63 158H100.333C101.333 158 102.333 157.667 103 157C103.667 156.333 104 155.333 104 154.333V113C104 112.667 104 112.667 104 112.333L122 83.3333C122.333 83 122.333 82.3333 122.667 81.6667C123 81 123.333 80 123 79L118 59.3333ZM66.6667 83.6667L74.6667 71L77 80.3333L66.6667 97V83.6667ZM66.6667 150V113.667H96.3333V150H66.6667ZM98.6667 106H70.3333L84.3333 83.6667H112.333L98.6667 106ZM84 76L81 64.3333H111.333L114.333 76H84Z" fill="black" />
                      </g>
                  </g>
              </g>
          </g>
      </svg>
    </div>
  </div>
</template>

<style scoped>

.mix-rounded{
    border-radius: 0px 13px 200px 94px;
    -moz-border-radius: 0px 13px 200px 94px;
    -webkit-border-radius: 0px 13px 200px 94px;
    border: 0px solid #000000;
}

.head-title{
  font-family: 'Luckiest Guy', cursive;
  letter-spacing: 8px;
  color:#F0A70B; 
  /* text-shadow: 0px 0px 10px #F0A70B; */

}
/* .bg-head{
  background: #f79d00;   fallback for old browsers 
  background: -webkit-linear-gradient(to bottom, #2f7744, #f79d00);  /* Chrome 10-25, Safari 5.1-6 
  background: linear-gradient(to bottom, #2f7744, #f79d00); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ 

} */
.bg-head-dark{
  background-color: #171717;
}
.bg-head {
  background: linear-gradient(190deg, #2f7744, #f79d00, #2bb937, #050504);
  background-size: 800% 800%;

	-webkit-animation: gradient 0.5s ease infinite;
	animation: gradient 15s ease infinite;
}

@-webkit-keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}

@keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}
/* switch styles */
.switch{ 
  display: block;
  widows: 10%;
  height: 20%;
}
#marco vector{
  fill: #fff;
}

</style>