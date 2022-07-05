<template>
  <div class="wedding-invitation-rakha-sheila">
  <section id="modal" class="relative main-2 h-screen w-full flex items-center justify-center text-center bg-cover bg-center" >
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-gray-800 opacity-75"></div>
    <main class="px-4 sm:px-6 lg:px-8 z-10">
      <div class="text-center">
        <h3 style = "text-transform:capitalize;" v-if="name" class="animate fade-in-dear fadeIn text-2xl mb-3 tracking-tight leading-10 font-medium sm:text-4xl text-white sm:leading-none md:text-3xl">
          Dear {{name}} {{partner ? `& ${partner}` : ''}}
        </h3>
        <h2 class="animate fade-in-name fadeIn text-2xl tracking-tight leading-10 font-medium sm:text-4xl text-white sm:leading-none md:text-4xl">
          UNDANGAN PERNIKAHAN 
        </h2>
        <div class="flex justify-center w-full my-3 sm:my-5 sm:text-md sm:max-w-xl sm:mx-auto md:mt-5 text-white">
          <span class="animate fade-left-rakha fadeInLeft text-top text-2xl md:text-3xl">Rakha</span>
          <span class="animate fade-in-name fadeIn text-middle text-6xl md:text-8xl">&</span>
          <span class="animate fade-right-sheila fadeInRight text-bottom text-2xl md:text-3xl">Sheila</span>
        </div>
        <div class="mt-5 sm:mt-8 sm:flex justify-center">
          <div class="rounded-md shadow">
            <button
              class="animate fade-down-button fadeInDown fa border-2 text-md md:text-2xl hover:bg-white hover:text-black text-white border-white px-8 py-3 rounded-md"
              @click="onFirst"
            >
              Buka Undangan
            </button>
          </div>
        </div>
      </div>
    </main>
  </section>

  <section id="main" class="hidden relative main-1 h-screen w-full flex items-center justify-center text-center bg-cover bg-center">
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-gray-800 opacity-75"></div>
      <div class="px-4 sm:px-6 lg:px-8 z-10">
      <div class="text-center">
        <h2 class="text-2xl tracking-tight leading-10 font-medium sm:text-3xl text-white sm:leading-none md:text-3xl">
          KAMI MENGUNDANG ANDA MENGHADIRI ACARA PERNIKAHAN
        </h2>
        <div class="flex justify-center w-full my-3 sm:my-5 sm:text-md sm:max-w-xl sm:mx-auto md:my-8 text-white">
          <span class="text-top text-2xl md:text-5xl">Rakha</span>
          <span class="text-middle text-6xl md:text-8xl">&</span>
          <span class="text-bottom text-2xl md:text-5xl">Sheila</span>
        </div>
        <no-ssr>
          <flip-countdown deadline="2022-08-06 00:00:00"></flip-countdown>
        </no-ssr>
        <div class="mt-5 sm:mt-8 sm:flex justify-center">
          <a target="_blank" href="https://calendar.google.com/event?action=TEMPLATE&amp;tmeid=MHVmbXVmMjQzcjFsOGUzMjY4cnNqMGt1dnIgcmFraGFndXN0aXdhcmRoYW5hQG0&amp;tmsrc=rakhagustiwardhana%40gmail.com" class="rounded-md shadow">
            <button
              class="border-2 focus:bg-black bg-second hover:text-white text-black border-white px-8 md:px-10 py-3 rounded-md"
            >
            <div class="flex justify-center items-center relative">
              <div class="mr-3">
                <!-- <a target="_blank" href="https://calendar.google.com/event?action=TEMPLATE&amp;tmeid=MHVmbXVmMjQzcjFsOGUzMjY4cnNqMGt1dnIgcmFraGFndXN0aXdhcmRoYW5hQG0&amp;tmsrc=rakhagustiwardhana%40gmail.com"><img border="0" src="https://www.google.com/calendar/images/ext/gc_button1_en.gif"></a> -->
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </div>
              Ingatkan Saya
              </div>
            </button>
          </a>
        </div>
      </div>
    </div>
  </section>

  <section id="main2" class="hidden main-1 h-full relative w-full pt-7 pb-7 md:pt-20 md:pb-24 flex items-center justify-center bg-cover bg-center">
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-white opacity-75"></div>
    <p data-aos="fade-down" data-aos-duration="500" class="max-w-5xl mx-auto text-center text-md md:text-xl mb-5 md:mb-8 relative text-lato">Dengan kerendahan hati, kami mengundang Bapak/Ibu/Saudara/Saudari untuk menghadiri pernikahan kami dan memberikan restu kepada kedua mempelai</p>   
    <div class="box-border flex flex-col items-center content-center px-8 mx-auto leading-6 text-black border-0 border-gray-300 border-solid md:flex-row max-w-7xl lg:px-16">
      <div data-aos="fade-left" data-aos-duration="1000" class="box-border relative w-full max-w-md px-4 mt-5 mb-4 -ml-5 text-center bg-no-repeat bg-contain border-solid md:ml-0 md:mt-0 md:max-w-none lg:mb-0 md:w-1/2 xl:pl-10">
          <img src="~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg" class="max-h-96 mx-auto pl-6 pr-5 xl:pl-16 xl:pr-20" style="-webkit-border-radius: 40% 0 40% 0; border-radius: 40% 0 40% 0; object-fit: cover; object-position: center;">
      </div>
      <div class="box-border order-first w-full text-center md:text-left text-black border-solid md:w-1/2 md:pl-10 md:order-none">
          <h2 data-aos="fade-up" data-aos-duration="1000" class="relative m-0 text-xl font-semibold leading-tight border-0 border-gray-300 lg:text-3xl md:text-2xl">
              Rakha Gusti Wardhana S.Kesos
          </h2>
          <p class="relative pt-2 m-0 leading-7 text-gray-700 border-0 border-gray-300 sm:pr-12 xl:pr-32 lg:text-lg">
              Putra pertama dari Bapak Agus Wardhana, S.E.
          </p>
          <p class="relative p-0 m-0 leading-7 text-gray-700 border-0 border-gray-300 sm:pr-12 xl:pr-32 lg:text-lg">
              &
          </p>
          <p class="relative pb-4 m-0 leading-7 text-gray-700 border-0 border-gray-300 sm:pr-12 xl:pr-32 lg:text-lg">
              Ibu Agustina, S.E.
          </p>
      </div>
    </div>
    <p class="relative text-center text-3xl leading-tight lg:text-8xl md:text-1xl">&</p>
    <div class="box-border flex flex-col items-center content-center px-8 mx-auto mt-2 leading-6 text-black border-0 border-gray-300 border-solid md:mt-20 xl:mt-0 md:flex-row max-w-7xl lg:px-16">
      <div class="box-border w-full text-center md:text-right text-black border-solid md:w-1/2 md:pl-6 xl:pl-28">
          <h2 data-aos="fade-up" data-aos-duration="1000" class="relative m-0 text-xl font-semibold leading-tight border-0 border-gray-300 lg:text-3xl md:text-2xl">
              Sheila Jasmine Meutia Azzara S.Sos
          </h2>
          <p class="relative pt-2 m-0 leading-7 text-gray-700 border-0 border-gray-300 lg:text-lg">
              Putri pertama dari Bapak Achmad Jani Subchan Maliki, S.Sos.
          </p>
          <p class="relative p-0 m-0 leading-7 text-gray-700 border-0 border-gray-300 lg:text-lg">
              &
          </p>
          <p class="relative pb-4 m-0 leading-7 text-gray-700 border-0 border-gray-300 lg:text-lg">
              Ibu dr. Dwi Rosaline Febrina
          </p>
      </div>
      <div data-aos="fade-right" data-aos-duration="1000" class="box-border relative w-full max-w-md px-4 mt-10 mb-4 text-center bg-no-repeat bg-contain border-solid md:mt-0 md:max-w-none lg:mb-0 md:w-1/2">
          <img src="~assets/_Self_Photo_Studio_Jakarta_-_Depok-2.webp" class="max-h-96 mx-auto sm:pr-6 xl:pl-10 lg:pr-32" style="object-fit: cover; object-position: center; -webkit-border-radius: 40% 0 40% 0; border-radius: 40% 0 40% 0;">
      </div>
    </div>
  </section>

  <section id="main3" class="hidden main-1 h-full relative w-full flex items-center justify-center bg-cover bg-center">
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-white opacity-75"></div>
    <h1 data-aos="fade-up" data-aos-duration="1000" class="relative text-center text-2xl md:text-3xl pt-20">Waktu & Tempat</h1>
    <div class="container mx-auto flex px-5 mt-8 pb-24 md:flex-row flex-col items-center">
      <div data-aos="fade-left" data-aos-duration="1000" class="relative lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
        <p class="mb-4 text-sm sm:text-xl">Sabtu, 6 Agustus 2022 <br /> 11.00-13.00 WIB</p>
        <h1 class="title-font sm:text-4xl text-xl mb-4 font-medium text-gray-900">
          Felfest Faculty Club Universitas Indonesia
        </h1>
        <p class="mb-8 text-sm sm:text-xl">Kampus UI, Jl. Prof. Dr. Miriam Budiardjo <br />
        Kel. Srengseng Sawah, Kec. Jagakarsa
        Jakarta Selatan
        </p>
        <div class="flex justify-center">
          <a href="https://www.google.com/maps/place/Felfest+UI+Faculty+Club+Universitas+Indonesia/@-6.3508732,106.8290213,17z/data=!3m1!4b1!4m5!3m4!1s0x2e69ec3a9517d101:0x895775594e85e9ac!8m2!3d-6.3508732!4d106.83121?hl=en" class="inline-flex text-gray-700 bg-gray-200 border-0 py-2 px-6 focus:outline-none hover:bg-gray-300 rounded text-lg">Lihat Map</a>
        </div>
      </div>
      <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
        <img data-aos="fade-right" data-aos-duration="1000" class="relative object-cover object-center rounded" alt="hero" src="https://tempatnikah.net/wp-content/uploads/2020/09/UI1.png">
      </div>
    </div>
  </section>  

  <section id="main4" class="hidden text-gray-700 body-font">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-wrap -m-4">
        <div class="p-4 w-full md:w-1/3">
          <div data-aos="fade-left" data-aos-duration="1000" class="flex rounded-lg h-full bg-gray-100 p-8 flex-col">
            <button @click="onModalQR" class="without-caption mx-auto image-link">
              <img src="~assets/QR.png" width="172" height="115" />  
            </button>
          </div>
        </div>
        <div class="p-2 md:p-4 w-full md:w-1/3">
          <div data-aos="flip-down" data-aos-duration="1000" class="flex rounded-lg h-full bg-gray-100 p-8 flex-col">
              <a target="_blank" href="https://www.myregistry.com/wedding-registry/sheila-jasmine-and-rakha-wardhana-jakarta-selatan-dki-jakarta/3227912/giftlist" class="py-2 px-4 bg-gray-500 text-white rounded hover:bg-gray-700 my-auto text-center"><i class="fas fa-times"></i> Klik di sini untuk mengirimkan hadiah fisik</a>
          </div>
        </div>
        <div class="p-2 md:p-4 w-full md:w-1/3">
          <div data-aos="fade-right" data-aos-duration="1000" class="flex rounded-lg h-full bg-gray-100 p-8 flex-col">
              <nuxt-link :to="partner ? `/rsvp?invitee=${name}&partner=${partner}` : name ? `/rsvp?invitee=${name}` : `/rsvp` " class="py-2 px-4 bg-gray-500 text-white text-center rounded hover:bg-gray-700 my-auto"><i class="fas fa-times"></i> Klik di sini untuk reservasi kehadiran Anda</nuxt-link>
          </div>
        </div>
      </div>
    </div>
  </section>
  <transition name="fade">
    <div v-if="isModalQR" class="fixed z-10 overflow-y-auto top-0 w-full left-0" id="modal">
      <div class="flex items-center justify-center min-height-100vh pt-4 px-4 pb-20 text-center sm:block sm:p-0">
        <div class="fixed inset-0 transition-opacity">
          <div class="absolute inset-0 bg-gray-900 opacity-75" />
        </div>
        <span class="hidden sm:inline-block sm:align-middle sm:h-screen">&#8203;</span>
        <div class="inline-block align-center bg-white rounded-lg text-left overflow-hidden shadow-xl transform transition-all sm:my-8 sm:align-middle sm:max-w-lg sm:w-full" role="dialog" aria-modal="true" aria-labelledby="modal-headline">
          <img src="~assets/QR.png" width="100%" height="auto" />  
          <div class="bg-gray-200 px-4 py-3 text-right">
            <button type="button" class="py-2 px-4 bg-gray-500 text-white rounded hover:bg-gray-700 mr-2" @click="onModalQR"><i class="fas fa-times"></i> Close QR</button>
          </div>
        </div>
      </div>
    </div>
  </transition>

  <section id="main7" class="hidden text-gray-700 bg-primer body-font">
    <div class="container px-5 py-24 mx-auto">
      <no-ssr>
        <carousel-3d id="main5" class="hidden" :autoplay="true" :autoplay-timeout="3000" :controls-visible="true" :controls-prev-html="'&#x2039; '" :controls-next-html="'&#x203A;'"  :controls-width="10" :controls-height="30" :clickable="false">    
          <slide  :index="0">
            <img src="~assets/_Self_Photo_Studio_Jakarta_-_Depok-5.webp" style="object-fit: cover; height: 100%;">
          </slide>
          <slide :index="1">
            <img src="~assets/_Self_Photo_Studio_Jakarta_-_Depok-6.webp" style="object-fit: cover; height: 100%;">
          </slide>
          <slide  :index="2">    
           <img src="~assets/_Self_Photo_Studio_Jakarta_-_Depok-7.webp" style="object-fit: cover; height: 100%;"> 
          </slide>
          <slide :index="3">
            <img src="~assets/_Self_Photo_Studio_Jakarta_-_Depok-8.webp" style="object-fit: cover; height: 100%;">    
          </slide>
          <slide :index="4">
            <img src="~assets/_Self_Photo_Studio_Jakarta_-_Depok-9.webp" style="object-fit: cover; height: 100%;">
          </slide>
          <slide :index="5">
            <img src="~assets/Self_Photo_Studio_Jakarta_-_Depok-10.webp" style="object-fit: cover; height: 100%;"> 
          </slide>
          <slide :index="6">
            <img src="~assets/_Self_Photo_Studio_Jakarta_-_Depok-3.webp" style="object-fit: cover; height: 100%;"> 
          </slide>
        </carousel-3d>
      </no-ssr>
    </div>
  </section>
  <section id="main6" class="hidden bg-primer">
    <div class="container mx-auto px-6 text-center py-20">
      <h2 class="mb-6 text-xl md:text-4xl font-bold text-center text-black">Terimakasih</h2>
      <p class="my-4 text-2xl text-black">Terima kasih telah menghadiri pernikahan kami secara virtual.</p>
    </div>
  </section>
  
  <footer id="footer" class="hidden text-gray-700 body-font">
    <div class="bg-gray-200">
      <div class="container mx-auto py-4 px-5 flex justify-center flex-wrap flex-col sm:flex-row">
        <p class="text-gray-500 text-sm text-center sm:text-left">© Copyright 2022 —
          <a href="https://twitter.com/knyttneve" class="text-gray-600 ml-1" target="_blank" rel="noopener noreferrer">@sukronn_</a>
        </p>
      </div>
    </div>
  </footer>
  <a href="https://github.com/mertJF/tailblocks" id="play-btn" class="hidden rounded-full w-12 h-12 bg-gray-100 fixed bottom-0 right-0 flex items-center justify-center text-gray-800 mr-8 mb-8 shadow-sm border-gray-300 border" target="_blank"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
      <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path>
    </svg>
  </a>
  </div>
</template>

<script>
import FlipCountdown from 'vue2-flip-countdown';

export default {
  name: 'IndexPage',
  data() {
    return {
      isOpen: true,
      slides: 7,
      onShow: false,
      name: this.$route.query.invitee,
      partner: this.$route.query.partner ? this.$route.query.partner : null
    };
  },
  components: { 
    FlipCountdown,
  },

  methods: {
    onFirst() {
      document.getElementById("modal").style.transform="translateY(-100%)";
      document.getElementById("modal").style.transition=" all 1.2s";
      document.getElementById("modal").style.zIndex="8";
      document.getElementById("play-btn").style.display="flex";
      document.getElementById("main").style.display="flex";
      document.getElementById("main2").style.display="block";
      document.getElementById("main3").style.display="block";
      document.getElementById("main4").style.display="inherit";
      document.getElementById("main5").style.display="block";
      document.getElementById("main6").style.display="block";
      document.getElementById("main7").style.display="block";
      document.getElementById("footer").style.display="block";
    },
    // toggleFirst(){
    //   document.getElementById('modals').classList.toggle('hidden');
    // },
    onModalQR() {
      this.onShow = !this.onShow;
      console.log(this.onShow)
    }
  },
  computed: {
    isModalQR() {
      return this.onShow;
    }
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Vidaloka&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lato&display=swap');

*{
  font-family: 'Vidaloka';
}

.text-lato{
  font-family: 'Lato' !important;
}

#modal{
  background-image: url('~assets/_Self_Photo_Studio_Jakarta_-_Depok-2.webp');
}

#main{
  background-image: url('~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg');
  /* background-size: cover; */
}

#main2{
  /* background-image: linear-gradient(180deg, #B3DEEF, #E6E6FA); */
  background-image: url('~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg');

}

#main3{
  background-image: url('~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg');
  /* background-image: linear-gradient(180deg, #E6E6FA, #B3DEEF ); */
}

#main4{
  background-color: #B3DEEF;
}

/* .carousel-3d-container { */
  .carousel-3d-container .carousel-3d-slide {
    padding: 20px;    
  }
    .carousel-3d-slide .title { font-size: 22px; }

/* } */

.bg-primer{
  background-color: #B3DEEF !important;
}

.bg-second{
  background-color: #E6E6FA !important;
}

.main-1 {
  position: relative;
}

.main-2 {
  position: absolute;
  top: 0;
}

.flip-clock__piece{
  color: #B3DEEF !important;
}
.flip{
  color: #B3DEEF !important;
}
.flip-card__top{
  color: #B3DEEF !important;
}
.flip-card__back::before{
  color: #B3DEEF !important;
}
.flip-card__bottom{
  color: #E6E6FA !important;
}
.flip-card__back-bottom{
  color: #E6E6FA !important;
}

.text-top {
  align-self: flex-start;
}

.text-middle {
  align-self: center;
}

.text-bottom {
  align-self: flex-end;
}

.animate {
  -webkit-animation-duration: 1s;
  animation-duration: 1s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
}

.fade-in-dear {
  -webkit-animation-delay: 0.5s;
  -moz-animation-delay: 0.5s;
  animation-delay: 0.5s;
}

.fade-in-name, .fade-left-rakha, .fade-right-sheila, .fade-down-button {
  -webkit-animation-delay: 1.0s;
  -moz-animation-delay: 1.0s;
  animation-delay: 1.0s;
}

@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }

  to {
    opacity: 1;
  }
}
@keyframes fadeIn {
  from {
    opacity: 0;
  }

  to {
    opacity: 1;
  }
}
.fadeIn {
  -webkit-animation-name: fadeIn;
  animation-name: fadeIn;
}

@-webkit-keyframes fadeInLeft {
  from {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
  }

  to {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}
@keyframes fadeInLeft {
  from {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
  }

  to {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

.fadeInLeft {
  -webkit-animation-name: fadeInLeft;
  animation-name: fadeInLeft;
}

@-webkit-keyframes fadeInRight {
  from {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
  }

  to {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}
@keyframes fadeInRight {
  from {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
  }

  to {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}

.fadeInRight {
  -webkit-animation-name: fadeInRight;
  animation-name: fadeInRight;
}

.fadeInDown {
  -webkit-animation-name: fadeInDown;
  animation-name: fadeInDown;
}
@-webkit-keyframes fadeInDown {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -100%, 0);
    transform: translate3d(0, -100%, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}
@keyframes fadeInDown {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -100%, 0);
    transform: translate3d(0, -100%, 0);
  }
  100% {
    opacity: 1;
    -webkit-transform: none;
    transform: none;
  }
}
</style>
