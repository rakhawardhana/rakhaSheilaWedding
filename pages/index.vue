<template>
  <div class="wedding-invitation-rakha-sheila max-w-screen max-h-screen">
  <client-only>
  <section id="modal" class="relative main-2 max-w-screen max-h-screen h-screen w-full flex items-center justify-center text-center bg-cover bg-center" >
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-gray-800 opacity-75"></div>
    <main class="px-4 sm:px-6 lg:px-8 z-10">
      <div class="text-center">
        <h3 style="text-transform:capitalize;" v-show="name" class="animate fade-in-dear fadeIn text-3xl mb-8 tracking-tight leading-10 font-medium sm:text-4xl text-white sm:leading-none md:text-3xl">
          Dear <span class="italic">{{name}} {{partner ? `& ${partner}` : ''}},</span>
        </h3>
        <h2 class="animate fade-in-name fadeIn text-2xl tracking-tight leading-10 font-medium sm:text-4xl text-white sm:leading-none md:text-4xl">
          THE WEDDING OF
        </h2>
        <div class="flex justify-center mb-5 w-full my-3 sm:my-5 sm:text-md sm:max-w-xl mt-4 sm:mx-auto md:mt-6 text-white">
          <span class="animate fade-left-rakha fadeInLeft text-top text-dancing text-5xl md:text-5xl">Eric</span>
          <span class="animate fade-in-name p-4 fadeIn text-middle text-dancing text-3xl md:text-4xl">&amp;</span>
          <span class="animate fade-right-sheila fadeInRight text-bottom text-dancing text-5xl md:text-5xl">Listi</span>
        </div>
        <div class="mt-5 sm:mt-8 sm:flex justify-center">
          <div class="rounded-md shadow">
            <button
              class="animate fade-down-button fadeInDown  fa border-2 text-xl md:text-2xl hover:bg-white hover:text-black text-white border-white px-8 py-3 rounded-md"
              @click="onFirst"
            >
              Open Invitation
            </button>
          </div>
        </div>
      </div>
    </main>
  </section>

  <section id="main" class="hidden lo relative main-1 h-screen w-full flex items-center justify-center text-center bg-cover bg-center">
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-gray-800 opacity-75"></div>
      <div class="px-4 sm:px-6 lg:px-8 z-10">
      <div class="text-center">
        <h2 class="text-2xl tracking-tight leading-10 font-medium sm:text-3xl text-white sm:leading-none md:text-3xl">
          We Invite You To Our Wedding
        </h2>
        <div class="flex justify-center w-full mb-9 mt-6 my-3 sm:my-5 sm:text-md sm:max-w-xl sm:mx-auto md:my-8 text-white">
          <span class="text-top text-5xl text-dancing md:text-6xl">Eric</span>
          <span class="text-middle p-4 text-3xl text-dancing md:text-5xl">&amp;</span>
          <span class="text-bottom text-5xl text-dancing md:text-6xl">Listi</span>
        </div>
        <no-ssr>
          <flip-countdown deadline="2022-09-18 00:00:00"></flip-countdown>
        </no-ssr>
        <div class="mt-8 sm:mt-8 sm:flex justify-center">
          <a target="_blank" href="https://calendar.google.com/event?action=TEMPLATE&tmeid=NGtwNDRrOHQ0bXFtcmJuOWowcDVoYzdidHAgc3Vrcm9ubjI0QG0&tmsrc=sukronn24%40gmail.com" class="rounded-md shadow">
            <button
              class="border-2 focus:bg-black bg-second hover:text-white text-black border-white px-8 md:px-10 py-3 rounded-md"
            >
            <div class="flex justify-center items-center relative">
              <div class="mr-3">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </div>
              SAVE THE DATE
              </div>
            </button>
          </a>
        </div>
      </div>
    </div>
  </section>

  <section id="main2" class="hidden main-1 h-full relative w-full pt-7 pb-7 md:pt-20 md:pb-24 flex items-center justify-center bg-cover bg-center">
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-white opacity-75"></div>
    <p data-aos="fade-down" data-aos-duration="500" class="max-w-5xl px-8 text-serrat md:px-3 mx-auto italic text-center md:text-blue-400 text-blue-300 text-md md:text-xl mb-10 md:mb-10 relative">"And over all these virtues put on love. Which binds them all together in perfect unity."<br/>Colossians 3:14</p>   
    <p data-aos="fade-down" data-aos-duration="500" class="max-w-5xl px-8 mx-auto text-center text-slab text-md md:text-xl mb-5 md:mb-8 relative">By the grace and blessing of God We cordially request the honour of your presence At the wedding of our beloved children</p>   
    <div class="flex relative justify-center items-center w-full md:mb-3 lg:mb-16">
      <div class="p-4 md:w-full lg:w-10/12">
        <div class="ce-mo__picture"></div>
        <div style="border-bottom: solid 2px black">
          <h2 data-aos="fade-up" data-aos-duration="1000" class="relative text-center text-jose text-2xl md:text-3xl pb-3 pt-6">Eric</h2>
        </div>
        <p class="mb-1 mt-3 text-sm text-center text-jose sm:text-xl">Eric Ivan, S.T.,M.M.</p>
        <p class="mb-1 text-sm text-center text-slab sm:text-xl">The son of</p>
        <p class="mb-1 text-sm text-center text-slab sm:text-xl">Mr.Drs. Gozari Effendy</p>
        <p class="mb-1 text-sm text-center text-slab sm:text-xl">&amp;</p>
        <p class="mb-1 text-sm text-center text-slab sm:text-xl">Mrs. Liem Widaria Lindy</p>

      </div>
      <div class="p-4 md:w-full lg:w-10/12">
        <div class="ce-wo__picture"></div>
        <div style="border-bottom: solid 2px black">
          <h2 data-aos="fade-up" data-aos-duration="1000" class="relative text-center text-jose text-2xl md:text-3xl pb-3 lg:pb-3 pt-6">Listi</h2>
        </div>
        <p class="mb-1 mt-3 text-sm text-center text-jose sm:text-xl">Koe Listiyani,S.E</p>
        <p class="mb-1 text-sm text-center text-slab sm:text-xl">The daughter of</p>
        <p class="mb-1 text-sm text-center text-slab sm:text-xl">Mr. (+) Muliadi Susanto</p>
        <p class="mb-1 text-sm text-center text-slab sm:text-xl">&amp;</p>
        <p class="mb-1 md:mb-1 text-sm text-center text-slab sm:text-xl">Mrs. Koe Lie Hoa</p>
      </div>
    </div>
  </section>

  <section id="main3" class="ada hidden main-1 h-full relative w-full flex items-center justify-center bg-cover bg-center">
      <div class="absolute top-0 right-0 bottom-0 left-0 bg-white opacity-70"></div>
      <h1 data-aos="fade-up" data-aos-duration="1000" class="relative text-center text-2xl text-dancing lg:mb-16  md:text-3xl pt-20">Time & Place</h1>
      <div class="container mx-auto flex px-5 mt-2 pb-24 md:flex-row flex-col justify-center text-center items-center">
        <div data-aos="fade-left" data-aos-duration="1000" class="relative lg:flex-grow md:w-3/5 flex flex-col md:text-left p-4 md:mb-0 items-center text-center" style="box-shadow: 0 3px 1px -2px rgb(0 0 0 / 8%), 0 2px 2px 0 rgb(0 0 0 / 14%), 0 1px 5px 0 rgb(0 0 0 / 12%);">
          <div class="block md:flex md:justify-center items-center w-full md:mb-3 lg:mb-16">
            <div class="p-4 md:w-full lg:w-10/12">
              <img src="~assets/akad.png" width="110" height="auto" class="mx-auto">
              <div style="border-bottom: solid 2px black">
                <h2 data-aos="fade-up" data-aos-duration="1000" class="relative text-center text-2xl md:text-3xl pb-3 pt-6">Holy Matrimony</h2>
              </div>
              <p class="mb-4 pt-3 text-sm text-center sm:text-xl">Sunday, 18 September 2022</p>
                <div class="flex justify-center">
                  <div class="flex-contents">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mb-2 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                    </svg>
                    <p class="mr-3">12.00 - 13.00 WIB</p>
                  </div>
                  <div class="flex-contents">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mb-2 mx-auto">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" />
                      <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" />
                    </svg>
                    <a target="_blank" href="https://www.google.com/maps/dir//ndc+greenville/@-6.171528,106.7091575,12z/data=!3m1!4b1!4m9!4m8!1m1!4e2!1m5!1m1!1s0x2e69f65121e68943:0x99db85cf1165c8b2!2m2!1d106.7791981!2d-6.1715326" class="ml-3" style="color: #0000EE;">NDC GREEN VILLE MAISONETTE 3rd FLOOR</a>
                  </div>
                </div>
              <p class="mb-4 pt-3 text-sm text-center sm:text-xl">Blok FA No. 4-7 Jl. Tanjung Duren Barat Duri Kepa, West Jakarta</p>
            </div>
            <div class="p-4 md:w-full lg:w-10/12">
              <img src="~assets/resepsi.png" width="80" height="auto" class="mx-auto">
              <div style="border-bottom: solid 2px black">
                <h2 data-aos="fade-up" data-aos-duration="1000" class="relative text-center text-2xl md:text-3xl pb-3 pt-6">Wedding Reception</h2>
              </div>
              <p class="mb-4 pt-3 text-sm text-center sm:text-xl">Sunday, 18 September 2022</p>
              <div class="flex justify-center">
                  <div class="flex-contents">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mb-2 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                    </svg>
                    <p class="mr-2">18.30 - 21.00 WIB</p>
                  </div>
                  <div class="flex-contents">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mb-2 mx-auto">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" />
                      <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" />
                    </svg>
                    <a target="_blank" href="https://www.google.com/maps/dir//fortune+star+function+hall/@-6.1328447,106.74539,12z/data=!3m1!4b1!4m9!4m8!1m1!4e2!1m5!1m1!1s0x2e6a1dafaef74bcf:0x82c19e71b63f4356!2m2!1d106.8154306!2d-6.1328492" class="ml-2" style="color: #0000EE;">FORTUNE STAR FUNCTION HALL RUBY BALLROOM</a>
                  </div>
                </div>
              <p class="mb-4 pt-3 text-sm text-center sm:text-xl">Jl. Kunir No. 2 Pinangsia, West Jakarta</p>
              <br />
            </div>
          </div>
          <!-- <h1 class="title-font sm:text-4xl text-xl mb-4 font-medium text-gray-900">
            Felfest Faculty Club <br/> Universitas Indonesia
          </h1>
          <p class="mb-4 text-sm justify-center items-center text-center sm:text-xl">Kampus UI, Jl. Prof. Dr. Miriam Budiardjo <br />
          Kel. Srengseng Sawah, Kec. Jagakarsa <br/>
          Jakarta Selatan
          </p>
          <div class="flex justify-center">
            <a target="_blank" href="https://www.google.com/maps/place/Felfest+UI+Faculty+Club+Universitas+Indonesia/@-6.3508732,106.8290213,17z/data=!3m1!4b1!4m5!3m4!1s0x2e69ec3a9517d101:0x895775594e85e9ac!8m2!3d-6.3508732!4d106.83121?hl=en" class="inline-flex text-gray-700 bg-gray-200 border-0 py-2 px-6 focus:outline-none hover:bg-gray-300 rounded text-lg" style="border: 1px solid black;">Lihat Map</a>
          </div> -->
        </div>
      </div>
  </section>
  <section id="main7" class="hidden bg-protocol main-1 h-full relative bg-cover w-full bg-center">
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-white opacity-75"></div>
    <h1 data-aos="fade-up" data-aos-duration="1000" class="text-center pt-20 text-4xl px-6 text-dancing relative">Health Protocol</h1>
    <div data-aos="fade-left" data-aos-duration="1000" class="container relative px-5 py-12 mx-auto">
      <div class="grid grid-cols-2 md:grid-cols-2 lg:grid-cols-4 gap-6">
        <div class="border-2 border-gray-300 rounded-xl p-6 bg-gray-100">
            <img src="~assets/mask.png" width="110" height="auto" class="mx-auto">
            <p class="text-center">Use Mask</p>
        </div>
        <div class="border-2 border-gray-300 rounded-xl p-6 bg-gray-100">
            <img src="~assets/distance.png" width="160" height="auto" class="mx-auto">
            <p class="text-center">Social Distancing</p>
        </div>
        <div class="border-2 border-gray-300 rounded-xl p-6 bg-gray-100">
            <img src="~assets/washhand.png" width="160" height="200px;" class="mx-auto">
            <p class="text-center">Hand Sanitizer</p>
        </div>
        <div class="border-2 border-gray-300 rounded-xl p-6 bg-gray-100">
            <img src="~assets/tempt.png" width="160" height="auto" class="mx-auto">
            <p class="text-center">Fit. Body temp < 37° </p>
        </div>
      </div>
    </div>

    <div class="container px-5 py-12 mx-auto">
      <div class="flex flex-wrap -m-4">
        <div class="p-2 md:p-4 w-full md:w-1/2 relative">
          <div data-aos="flip-down" data-aos-duration="1000" class="relative text-center items-center justify-center flex rounded-lg h-full bg-gray-100 p-8 flex-col">
              <img src="~assets/aside.png" style="position: absolute; left: 0;  top:20px; height:92%; width:37%; " />
              <h2 class="text-2xl pb-5 md:text-3xl">RSVP</h2>
              <p class="mb-8 text-center md:mb-15">Please help us to prepare for the event better by confirming your attendance at our wedding on the following form:</p>
              <nuxt-link style="font-size: 20px;" :to="partner ? `/rsvp?invitee=${name}&partner=${partner}` : name ? `/rsvp?invitee=${name}` : `/rsvp` " class="flex w-8/12 justify-center items-center py-2 px-4 bg-gray-500 text-white text-center rounded hover:bg-gray-700 my-auto shadow-md">Reservation</nuxt-link>
          </div>
        </div>
        <div class="p-2 md:p-4 w-full md:w-1/2 relative">
          <div data-aos="fade-right" data-aos-duration="1000" class="text-center items-center justify-center  flex rounded-lg h-full bg-gray-100 p-8 flex-col">
              <img src="~assets/aside.png" style="position: absolute;  top:20px; right: 0px; height:92%; width:37%; transform: scaleX(-1);" />
              <h2 class="text-2xl pb-5 md:text-3xl">WEDDING GIFT</h2>
              <p class="text-center mb-8 md:mb-15">To minimize Covid transmission through physical contact, we facilitate Invited Guests to be able to give a token of love through the following online transactions: </p>
              <button style="font-size: 20px;" @click="onModalQR" class="py-2 w-8/12 px-4 bg-gray-500 text-white rounded hover:bg-gray-700 my-auto shadow-md">Send Gift</button>
          </div>
        </div>
      </div>
    </div>
  </section>  

  <!-- <section id="main4" class="hidden main-1 h-full relative w-full bg-center">
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-white opacity-75"></div>
    <div class="container px-5 py-12 mx-auto">
      <div class="flex flex-wrap -m-4">
        <div class="p-2 md:p-4 w-full md:w-1/2 relative">
          <div data-aos="flip-down" data-aos-duration="1000" class="relative text-center items-center justify-center flex rounded-lg h-full bg-gray-100 p-8 flex-col">
              <img src="~assets/aside.png" style="position: absolute; left: 0;  top:20px; height:92%; width:37%; " />
              <h2 class="text-2xl pb-5 md:text-3xl">RSVP</h2>
              <p class="mb-8 text-center md:mb-15">Mohon bantu kami untuk mempersiapkan acara dengan lebih baik dengan mengkonfirmasi kehadiran Anda pada acara pernikahan kami pada form berikut:</p>
              <nuxt-link style="font-size: 20px;" :to="partner ? `/rsvp?invitee=${name}&partner=${partner}` : name ? `/rsvp?invitee=${name}` : `/rsvp` " class="flex w-8/12 justify-center items-center py-2 px-4 bg-gray-500 text-white text-center rounded hover:bg-gray-700 my-auto shadow-md">Reservasi</nuxt-link>
          </div>
        </div>
        <div class="p-2 md:p-4 w-full md:w-1/2 relative">
          <div data-aos="fade-right" data-aos-duration="1000" class="text-center items-center justify-center  flex rounded-lg h-full bg-gray-100 p-8 flex-col">
              <img src="~assets/aside.png" style="position: absolute;  top:20px; right: 0px; height:92%; width:37%; transform: scaleX(-1);" />
              <h2 class="text-2xl pb-5 md:text-3xl">WEDDING GIFT</h2>
              <p class="text-center mb-8 md:mb-15">To minimize Covid transmission through physical contact, we facilitate Invited Guests to be able to give a token of love through the following online transactions: </p>
              <button style="font-size: 20px;" @click="onModalQR" class="py-2 w-8/12 px-4 bg-gray-500 text-white rounded hover:bg-gray-700 my-auto shadow-md">Send Gift</button>
          </div>
        </div>
      </div>
    </div>
  </section> -->

  <section id="main-slider" class="hidden main-1 h-full relative w-full bg-center bg-cover">
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-gray-700 opacity-75"></div>
    <!-- <no-ssr>
        <carousel-3d :width="500" :height="400" data-aos="fade-right" data-aos-duration="1000" id="main5" class="hidden" :display="6" :autoplay="true" :autoplay-timeout="3000">    
          <slide  :index="0">
            <img  src="~assets/el_portrait1.jpeg" style="object-fit: cover; min-width: 362px; height: 100%;">
          </slide>
          <slide :index="1">
            <img   src="~assets/el_portrait2.jpeg" style="object-fit: cover; min-width: 362px; height: 100%;"> 
          </slide>
          <slide :index="2">
            <img   src="~assets/el_portrait3.jpeg" style="object-fit: cover; min-width: 362px;height: 100%;"> 
          </slide>

          <slide :index="3">
            <img   src="~assets/el_portrait4.jpeg" style="object-fit: cover; min-width: 362px; height: 100%;">    
          </slide>
          <slide :index="4">
            <img   src="~assets/el_portrait5.jpeg" style="object-fit: cover; min-width: 362px; height: 100%;">
          </slide>
          <slide :index="5">
            <img   src="~assets/lamaran1 copy.jpg" style="object-fit: cover; min-width: 362px;height: 100%;"> 
          </slide>
          <slide :index="6">
            <img src="~assets/lamaran2.jpg" style="object-fit: cover; min-width: 362px; height: 100%;">    
          </slide>
          <slide :index="7">
            <img src="~assets/undangan/revisi1.jpeg" style="object-fit: cover; min-width: 362px; height: 100%;">
          </slide>
          <slide :index="8"> 
            <img src="~assets/undangan/revisi5.jpeg" style="object-fit: cover; min-width: 362px;height: 100%;"> 
          </slide>
          <slide :index="9">
            <img src="~assets/undangan/revisi6.jpeg" style="object-fit: cover; min-width: 362px; height: 100%;">    
          </slide>
          <slide :index="10">
            <img src="~assets/wisuda2.jpg" style="object-fit: cover; min-width: 362px; height: 100%;">
          </slide>
        </carousel-3d>
      </no-ssr> -->

      <img src="../assets/el_portrait5.jpeg" alt="Eric & Listi Wedding" class="img--img-a mb-2 relative">


      <div class="container--img relative">
        <div>
            <img src="../assets/el_portrait2.jpeg" alt="Eric & Listi Wedding" class="img--img">
        </div>

        <div>
            <img src="../assets/el_lands2.jpeg" alt="Eric & Listi Wedding" class="img--img mb-3 md:mb-11">
            <img src="../assets/el_landscape.jpeg" alt="Eric & Listi Wedding" class="img--img ">
        </div>

        <div>
            <img src="../assets/el_portrait4.jpeg" alt="Eric & Listi Wedding" class="img--img">
        </div>
        </div>
  </section>

  <!-- <transition name="fade">
    <div v-if="isModalPhoto" class="fixed flex inset-0 z-10 bg-transparent bg-opacity-75" id="modal2">
      <div class="flex self-center items-center justify-center w-full h-full p-8 max-h-fit">
        <div class="flex flex-col overflow-hidden bg-white rounded w-full max-h-full max-w-md">

          <div class="flex items-center justify-end p-4">
            <button @click="onModalPhoto('')" type="button">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
              </svg>
            </button>
          </div>

          <div class="relative overflow-y-auto p-4" :style="`background-image: url(${photo})`">
            
          </div>
        </div>
      </div>
    </div>
  </transition> -->

  <transition name="fade">
    <div v-if="isModalQR" class="fixed flex inset-0 z-10 bg-transparent bg-opacity-75" id="modal">
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-gray-800 opacity-75"></div>

      <!-- <img src="~/assets/el_portrait5.jpeg" id="background-modal" width="100%" height="auto" alt="Rakha Sheila Wedding" style="position: absolute;"> -->

      <!-- Remove the 'max-h-96' on the div below to use the height of the content -->
      <div class="flex self-center items-center justify-center w-full h-full p-8 max-h-fit">
        <!-- To adjust the width of the modal, change the 'max-w-md' on the div below to your liking -->
        <div class="flex relative flex-col overflow-hidden bg-white rounded w-full max-h-full max-w-md">

          <!-- <img src="~/assets/border-top.jpg" alt="Rakha Sheila Wedding" width="200" height="auto" style="position: absolute; left: -10px;"> -->
          <!-- <img src="~/assets/border-top.jpg" alt="Rakha Sheila Wedding" width="200" height="auto" style="transform: scaleX(-1); right: 0; position: absolute"> -->

          <!-- Header -->
          <div class="flex items-center justify-end p-4" style="position: absolute; right: 0; z-index: 10">
            <button @click="onModalQR" type="button">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
              </svg>
            </button>
          </div>

          <!-- Content -->
          <div class="relative overflow-y-auto p-8">
            <div class="flex items-center justify-center pb-4">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 8v13m0-13V6a2 2 0 112 2h-2zm0 0V5.5A2.5 2.5 0 109.5 8H12zm-7 4h14M5 12a2 2 0 110-4h14a2 2 0 110 4M5 12v7a2 2 0 002 2h10a2 2 0 002-2v-7" />
              </svg>
            </div>
            <!-- <div class="flex items-center justify-center pb-4">
              <h1 class="text-center">Jalan Zeni 3 No 22 RT07/RW03, Kelurahan Rawajati, Kecamatan Pancoran, Jakarta Selatan</h1>
            </div>
            <div class="flex items-center justify-center">
              <button class="py-1 px-3 bg-gray-500 mx-auto text-white rounded hover:bg-gray-700 my-auto" @click="copyAddress" style="font-size: 14px;">Copy Alamat</button>
            </div>
            <div class="text-center">
              <a href="#" class="arrow up">Up</a>
              <p style="color: red;">Copy Alamat diatas sebelum mengirimkan hadiah fisik</p>
              <a href="#" class="arrow down">Down</a>
            </div>
            <div class="flex items-center justify-center pb-4 mb-8">
              <a target="_blank" href="https://www.myregistry.com/wedding-registry/sheila-jasmine-and-rakha-wardhana-jakarta-selatan-dki-jakarta/3227912/giftlist" class="py-2 text-center px-4 bg-gray-500 text-white rounded hover:bg-gray-700">Kirim hadiah fisik</a>
            </div> -->
            <div class="items-center text-center mb-8">
              <div>
              <h1 class="font-bold">BCA</h1>
              <h1>Eric Ivan</h1>
              <div class="flex mb-4 items-center justify-center">
                  <p>6043983046</p>
                  <button class="items-center justify-center ml-3" @click="copyMandiri">
                    <svg class="items-center justify-center w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M384 96L384 0h-112c-26.51 0-48 21.49-48 48v288c0 26.51 21.49 48 48 48H464c26.51 0 48-21.49 48-48V128h-95.1C398.4 128 384 113.6 384 96zM416 0v96h96L416 0zM192 352V128h-144c-26.51 0-48 21.49-48 48v288c0 26.51 21.49 48 48 48h192c26.51 0 48-21.49 48-48L288 416h-32C220.7 416 192 387.3 192 352z"/></svg>
                  </button>
                </div>
              </div>
              
            </div>
            <img src="~assets/er_bca.png" width="100%" height="auto" />  

            <div class="flex items-center justify-center pb-4 pt-8">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 8v13m0-13V6a2 2 0 112 2h-2zm0 0V5.5A2.5 2.5 0 109.5 8H12zm-7 4h14M5 12a2 2 0 110-4h14a2 2 0 110 4M5 12v7a2 2 0 002 2h10a2 2 0 002-2v-7" />
              </svg>
            </div>

            <div class="items-center text-center mb-8">
              <h1 class="font-bold">Permata</h1>
              <h1>Eric Ivan</h1>
              <div class="flex mb-4 items-center justify-center">
                  <p>9809125499</p>
                  <button class="items-center justify-center ml-3" @click="copyPermata">
                    <svg class="items-center justify-center w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M384 96L384 0h-112c-26.51 0-48 21.49-48 48v288c0 26.51 21.49 48 48 48H464c26.51 0 48-21.49 48-48V128h-95.1C398.4 128 384 113.6 384 96zM416 0v96h96L416 0zM192 352V128h-144c-26.51 0-48 21.49-48 48v288c0 26.51 21.49 48 48 48h192c26.51 0 48-21.49 48-48L288 416h-32C220.7 416 192 387.3 192 352z"/></svg>
                  </button>
                </div>
              </div>

          </div>
        </div>
      </div>
    </div>
  </transition>

  <section id="main6" class="hidden main-1 h-full relative w-full bg-center">
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-gray-300 opacity-75"></div>
    <div class="container mx-auto px-6 text-center py-20">
      <h2 class="relative md:mb-4 text-4xl md:text-4xl font-bold text-center  text-gray-700">Thank You</h2>
      <p class="my-4 mb-5 relative text-xl text-gray-700">For Coming & Your Blessing</p>
      <div data-aos="fade-left" data-aos-duration="1000" class="flex relative justify-center w-full my-3 sm:my-5 sm:text-md sm:max-w-xl sm:mx-auto md:my-8 text-white">
          <span style="color: rgb(100 116 139);" class="text-top font-bold text-dancing text-cyan-300	text-5xl md:text-6xl">Eric</span>
          <span style="color: rgb(100 116 139);" class="text-middle p-5 text-4xl text-dancing text-cyan-300	md:text-5xl">&</span>
          <span style="color: rgb(100 116 139);" class="text-bottom font-bold text-dancing text-cyan-300 text-5xl md:text-6xl">Listi</span>
      </div>
      <p data-aos="fade-left" data-aos-duration="1000" class="italic my-4 mt-6 relative text-xl text-gray-600">
        <!-- “Everyone Comes With Baggage. Find Someone Who Loves You Enough To Help You Unpack." <br/>-<br/>Ted Mosby -->
                “There are two big days in any love story: the day you meet the girl of your dreams and the day you marry her.” <br/>- Ted Mosby

      </p>
    </div>
  </section>
  
  <!-- <footer id="footer" class="hidden text-gray-700 body-font">
    <div class="bg-gray-200">
      <div class="container mx-auto py-4 px-5 flex justify-center flex-wrap flex-col sm:flex-row">
        <p class="text-gray-500 text-sm text-center sm:text-left">© Copyright 2022 —
          <a href="https://twitter.com/knyttneve" class="text-gray-600 ml-1" target="_blank" rel="noopener noreferrer">@sukronn_</a>
        </p>
      </div>
    </div>
  </footer> -->
  

    <button @click="play" id="play-btn" class="hidden rounded-full w-6 h-6 bg-gray-100 fixed bottom-0 right-0 flex items-center justify-center text-gray-800 mr-8 mb-8 shadow-sm border-gray-300 border" target="_blank">
      <svg v-if="!music" class="items-center justify-center w-3 h-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M361 215C375.3 223.8 384 239.3 384 256C384 272.7 375.3 288.2 361 296.1L73.03 472.1C58.21 482 39.66 482.4 24.52 473.9C9.377 465.4 0 449.4 0 432V80C0 62.64 9.377 46.63 24.52 38.13C39.66 29.64 58.21 29.99 73.03 39.04L361 215z"/></svg>      
      <svg v-else class="items-center justify-center w-3 h-3"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512"><!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M272 63.1l-32 0c-26.51 0-48 21.49-48 47.1v288c0 26.51 21.49 48 48 48L272 448c26.51 0 48-21.49 48-48v-288C320 85.49 298.5 63.1 272 63.1zM80 63.1l-32 0c-26.51 0-48 21.49-48 48v288C0 426.5 21.49 448 48 448l32 0c26.51 0 48-21.49 48-48v-288C128 85.49 106.5 63.1 80 63.1z"/></svg>

      <audio id="play" controls src='@/assets/lagu.mp3' autoplay loop class="hidden rounded-full w-12 h-12 bg-gray-100 fixed bottom-0 right-0 flex items-center justify-center text-gray-800 mr-8 mb-8 shadow-sm border-gray-300 border" target="_blank">
      </audio>
    </button>
   
    </client-only>

  </div>
</template>

<script>
import FlipCountdown from 'vue2-flip-countdown';
import AOS from "aos";


export default {
  name: 'IndexPage',
  data() {
    return {
      isOpen: true,
      slides: 7,
      onShow: false,
      name: this.$route.query.invitee,
      partner: this.$route.query.partner ? this.$route.query.partner : null,
      music: false,
      onShowPhoto: false,
      photo: ''

    };
  },
  components: { 
    FlipCountdown,
  },

  methods: {
    onFirst() {
      this.play()

      document.getElementById("modal").style.transform="translateY(-100%)";
      document.getElementById("modal").style.transition=" all 1.2s";
      document.getElementById("modal").style.zIndex="8";
      document.getElementById("play-btn").style.display="flex";
      document.getElementById("main").style.display="flex";
      document.getElementById("main2").style.display="block";
      document.getElementById("main3").style.display="block";
      // document.getElementById("main4").style.display="inherit";
      // document.getElementById("main5").style.display="block";
      document.getElementById("main6").style.display="block";
      document.getElementById("main7").style.display="block";
      document.getElementById("main-slider").style.display="block";
      document.getElementById("main-slider").style.padding="40px";

      // document.getElementById("main7").style.display="block";
      // document.getElementById("footer").style.display="block";
      AOS.init()

    },
    // toggleFirst(){
    //   document.getElementById('modals').classList.toggle('hidden');
    // },
    onModalQR() {
      this.onShow = !this.onShow;
      console.log(this.onShow)
    },
    onModalPhoto(value){
      this.onShowPhoto = !this.onShowPhoto;
      this.photo = value
      console.log(value)
    },
    copyAddress(){
        navigator.clipboard.writeText('Jalan Zeni 3 No 22 RT07/RW03, Kelurahan Rawajati, Kecamatan Pancoran, Jakarta Selatan')
    },
    copyBCA(){
        navigator.clipboard.writeText('3970113206')
    },
    copyPermata(){
      navigator.clipboard.writeText('9809125499')
    },
    copyMandiri(){
        navigator.clipboard.writeText('6043983046')
    },
    copyBNI(){
        navigator.clipboard.writeText('1421370545')
    },
    copyGopay(){
        navigator.clipboard.writeText('082332403412')
    },
    copyOVO(){
        navigator.clipboard.writeText('085810336810')
    },
    playSound () {
        document.getElementById("play").play();
        this.music = true
    },
    pause(){
      document.getElementById("play").pause();
      this.music = false

    },
    play(){
        if(this.music === false){
          this.playSound()
        }else {
          this.pause()
        }
    }
  },
  computed: {
    isModalQR() {
      return this.onShow;
    },
    isModalPhoto() {
      return this.onShowPhoto;
    }
  }
}
</script>
<style lang="css">
@import url('https://fonts.googleapis.com/css2?family=Vidaloka&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lato&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;700;800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Tangerine&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Aphrodite Text&display=swap');
/* @import url('https://fonts.googleapis.com/css?family=GFS Didot'); */
@import url('https://fonts.googleapis.com/css?family=Sahitya&subset=devanagari');
@import url('https://fonts.googleapis.com/css2?family=GFS+Didot&display=swap');
@import url('https://fonts.googleapis.com/css?family=Dancing+Script&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Josefin+Slab&display=swap');

body {
  overflow-x: hidden;
}

*{
  /* font-family: "Palatino Linotype"; */
  /* font-family:  'GFS Didot' */
  font-family: 'GFS Didot', serif;
}

.text-dancing{
  font-family: 'Dancing Script';
}

.text-jose {
  font-family: 'Josefin Sans', sans-serif;
}

.text-slab {
  font-family: 'Josefin Slab', serif;
}

.text-lato{
  font-family: 'Lato' !important;
}

.text-serrat {
  font-family: 'Montserrat', sans-serif;
}
.text-vibe {
  font-family: 'Great Vibes', cursive;
}

#modal{
  background-image: url('~assets/el_portrait5.jpeg');
  background-size: cover;
}

/* #main{ */
  /* background-size: cover;   */
  /* animation: imageAnimation 36s linear 0s;  */

/* } */
#main-slider{
  background-color: rgb(241 245 249);
}

#main5{
  /* background-color: rgb(241 245 249); */

}
.lo{
    /* background-size: cover;   */
    animation: imageAnimation 36s linear 0s; 
      background-image: url('~assets/el_portrait4.jpeg');
    background-color: rgb(38 38 38);
    /* height: 100%;
    width: 100%; */
    opacity: 1

}
@keyframes imageAnimation { 
	0% {
      /* background-size: cover;   */
      background-color: rgb(38 38 38);

	    /* opacity: 0.85; */
       /* height: 100%;
    width: 100%; */
      min-height: 100%;
      width: 100%;
  
	    /* animation-timing-function: ease-in; */
      background-image: url('~assets/el_portrait2.jpeg');
	}
	30% {
      background-color: rgb(38 38 38);
      min-height: 100%;
      width: 100%;
      /* opacity: 0.85; */
      background-image: url("~assets/el_portrait1.jpeg");
	}
	55% {
      /* background-size: cover;   */
      background-color: rgb(38 38 38);
      min-height: 100%;
      min-width: 100%;
      /* opacity: 0.85; */

	    /* opacity: 1; */
	    /* transform: scale(1.1); */
      /* height: 100%;
       width: 100%; */
	    /* animation-timing-function: ease-in; */
      background-image: url("~assets/el_portrait5.jpeg");
	}
	70% {
      /* background-size: cover;   */
	    /* opacity: 0.75; */
      background-color: rgb(38 38 38);

	    /* transform: scale(1.15); */
      min-height: 100%;
      min-width: 100%;
	    /* animation-timing-function: ease-in; */
      background-image: url("~assets/el_portrait4.jpeg");
	}
  90% {
	    opacity: 1;
      background-color: rgb(38 38 38);
     
      min-height: 100%;
      min-width: 100%;      
      background-image: url("~assets/el_portrait3.jpeg");
	    /* animation-timing-function: ease-in; */
	}
	100% { 
      /* background-size: cover;   */
      background-color: rgb(38 38 38);
      opacity: 1;
      min-height: 100%;
      min-width: 100%;
      animation-timing-function: ease-in-out;
      background-image: url('~assets/el_portrait4.jpeg');
  }
}

@keyframes imageAnimationLagi { 
	0% {
	    /* opacity: 0; */
	    /* animation-timing-function: ease-in; */
      background-image: url('~assets/venue-1.jpeg');
      object-fit: cover; height: 100%;
	}
	8% {
	    /* opacity: 0; */
	    transform: scale(1.05);
	    /* animation-timing-function: ease-out; */
      background-image: url('~assets/venue-2.jpeg');
      object-fit: cover; height: 100%;


	}
	17% {
	   /* opacity: 1; */
	    transform: scale(1.1);
	    /* animation-timing-function: ease-in; */
      background-image: url('~assets/venue-3.jpeg');
      object-fit: cover; height: 100%;


	}
	25% {
	    /* opacity: 1; */
	    transform: scale(1.15);
	    /* animation-timing-function: ease-out; */
      background-image: url('~assets/venue-3.jpeg');
      object-fit: cover; height: 100%;

	}
  50% {
	    /* opacity: 1; */
	    transform: scale(1.2);
	    /* animation-timing-function: ease-out; */
      background-image: url('~assets/venue-5.jpeg');
      object-fit: cover; height: 100%;


	}
	100% { 
    /* opacity: 1; */
    	transform: scale(1.3);

      background-image: url('~assets/venue-5.jpeg');
      object-fit: cover; height: 100%;
  }
}

.ada {
   /* background-image: linear-gradient(180deg, #E6E6FA, #B3DEEF ); */
  /* animation: imageAnimation 36s linear 2s;  */
    /* background-image: url('~assets/venue-1.jpeg'); */
  background-image: url('~assets/bg-time.jpg');

  @media (max-width: 767px) {
    background-size: contain;
  }
}
#main2{
  /* background-image: linear-gradient(180deg, #B3DEEF, #E6E6FA); */
  background-image: url('~assets/bg-wed1.jpg');

  @media (max-width: 767px) {
    background-size: contain;
  }

}

#main-slider{
  /* background-image: linear-gradient(180deg, #B3DEEF, #E6E6FA); */
  background-image: url('~assets/bg-foto.jpg');

  @media (max-width: 767px) {
    background-size: contain;
  }

}

/* #main3{ */
  /* background-image: linear-gradient(180deg, #E6E6FA, #B3DEEF ); */
    /* animation: imageAnimationLagi 36s linear 2s;  */
    /* background-image: url('~assets/venue-1.jpeg'); */
    /* background-image: url('~assets/venue-3.jpeg'); */
/* } */

/* #main4{
  background-image: url('~assets/el_portrait2.jpeg');
} */

/* #main7{
  background-image: url('~assets/bg-protocol.jpg');
} */
.bg-protocol {
  background-image: url('~assets/bg-protocol.jpg');

  @media (max-width: 767px) {
    background-size: contain;
  }
}
#main6{
  /* background-color: #B3DEEF; */
  background-image: url('~assets/bg-thanks.jpg');
  background-size: cover;

  @media (max-width: 767px) {
    background-size: contain;
  }

}

/* .carousel-3d-container { */
  .carousel-3d-container .carousel-3d-slide {
    /* background-color: rgb(241 245 249); */

    padding: 20px;    
  }
    .carousel-3d-slide .title { font-size: 22px; }

/* .carousel-3d-controls{
    visibility: hidden;

} */
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

.carousel-3d-container{
  margin: 0 auto !important;
}

.carousel-3d-container .carousel-3d-slide {
  padding: 0 !important;
  border-radius: 10px !important;
}

/* .carousel-3d-slide{
  width: unset !important;
} */

.carousel-3d-slider {
  width: 370px !important;
}

@media (max-width: 768px) {
  .carousel-3d-slider {
    width: unset !important;
  }
}

@-webkit-keyframes uparrow {
  0% { -webkit-transform: translateY(0); opacity: 0.4 }
  100% { -webkit-transform: translateY(-0.4em); opacity: 0.9 }
}
@-webkit-keyframes downarrow {
  0% { -webkit-transform: translateY(0); opacity: 0.4 }
  100% { -webkit-transform: translateY(0.4em); opacity: 0.9 }
}

.arrow {
  border-color:transparent;
  border-style:solid;
  border-width:0 2em;
  display:block;
  height:0;
  margin:1em auto;
  opacity:0.4;
  text-indent:-9999px;
  transform-origin: 50% 50%;
  width:0;
}
.up {
  -webkit-animation: uparrow 0.6s infinite alternate ease-in-out;
  border-bottom:2em solid black;
}
.down {
  -webkit-animation: downarrow 0.6s infinite alternate ease-in-out;
  border-top:2em solid black;
}
#background-modal {
  @media (max-width: 767px) {
    display: none;
  }

  @media (min-width: 768px) {
    display: block;
  }
}

.ce-wo__picture {
  border-radius: 50%;
  margin: 0 auto;
  height: 210px;
  width: 210px;
  overflow: hidden;
  background:  url('~assets/ce_woman.jpeg');
  background-size: contain;
  background-position: center;

  @media (max-width: 767px) {
    height: 110px !important;
    width: 110px !important;
  }
}

.ce-mo__picture {
  border-radius: 50%;
  margin: 0 auto;
  height: 210px;
  width: 210px;
  overflow: hidden;
  background:  url('~assets/ce_man.jpeg');
  background-size: contain;
  background-position: center;

  @media (max-width: 767px) {
    height: 110px !important;
    width: 110px !important;
  }
}

.container--img {
  margin-top: 1rem;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 290px));
  grid-gap: 1rem;
  padding: 1rem;
  justify-content: center;
  box-shadow: 0 1px 1px #000;
}
.img--img {
  background-position: top;
  background-size: cover;
  height: auto;
  width: 290px;
  box-shadow: 0 2px 10px #000;
  cursor: pointer;
  transition: all 0.2s;
}
.img--img:hover {
  box-shadow: none;
  transform: scale(1.1);
}

.img--img-a {
  background-position: top;
  background-size: cover;
  height: auto;
  width: 690px;
  box-shadow: 0 2px 10px #000;
  cursor: pointer;
  margin: 0 auto;
  transition: all 0.2s;
}
.img--img-a:hover {
  box-shadow: none;
  transform: scale(1.1);
}
.flex-contents{
  @media (max-width: 767px) {
   width: 50%;
  }
}
</style>
