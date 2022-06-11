<template>
  <div class="wedding-invitation-rakha-sheila">
    <section id="main" class="w-full h-screen p-32 bg-center text-center bg-dunes main-1">
      <h1 class="text-5xl font-bold mb-2 bg-clip-text text-transparent bg-gradient-to-r from-blue-400 to-purple-500">WE INVITE YOU TO THE WEDDING OF</h1>
      <div class="flex justify-center w-full">
        <span class="text-top">Rakha</span>
        <span class="text-middle">&</span>
        <span class="text-bottom">Sheila</span>
      </div>
      <p>We are getting married!</p>
        <button class="py-3 px-8 bg-gray-400 hover:bg-gray-300 text-gray-800 hover:text-gray-900 rounded-lg hover:shadow-xl transition duration-300">Remind me</button>
    </section>

    <section id="modal" class="main-2 w-full h-screen p-32 bg-center text-center bg-dunes">
      <h1 class="text-5xl font-bold mb-2 bg-clip-text text-transparent bg-gradient-to-r from-blue-400 to-purple-500" data-aos="fade-up"
   data-aos-duration="1000">WE INVITE YOU TO THE WEDDING OF</h1>
      <div class="flex justify-center w-full">
        <span class="text-top animate-first-left">Rakha</span>
        <span class="text-middle">&</span>
        <span class="text-bottom animate-first-right">Sheila</span>
      </div>
      <div class="space-x-2">
        <button @click="onToggle" class="py-3 px-8 bg-gray-400 hover:bg-gray-300 text-gray-800 hover:text-gray-900 rounded-lg hover:shadow-xl transition duration-300">Open The Invitiation</button>
      </div>
    </section>

    <section id="main2" class="w-full h-screen p-32 bg-center text-center hehe main-3">
      <div class="flex justify-center w-full">
        <span class="wlwl"><hr /></span>
        <span class="wlwl border h-12">Rakha & Sheila</span>
        <span class="wlwl"><hr /></span>
      </div>
      <p data-aos="fade-up" data-aos-delay="300">It is an honor for us if you would attend our wedding virtually and give blessings to the bride and the groom.</p>

      <div class="flex flex-wrap -mx-2 mb-8 mt-8">
        <div class="w-full md:w-1/2 lg:w-1/2 px-2 mb-4">
          <div class="text-sm text-grey-dark text-right">
              <h1>Rakha Gusti Wardhana S.Kesos</h1>
              <p>Son of Agus Wardhana S.E</p>
              <p>&</p>
              <p>Agustina S.E</p>
          </div>
        </div>
        <div class="w-full lg:w-1/2 px-2">
          <div class="flex justify-center text-center">
          <img data-aos="zoom-in" data-aos-delay="500" class="rounded w-full sm:w-1/2 lg:w-1/2 h-auto shadow-2xl" src="~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg" alt="Book on top of a  map. A camera, magnifiying glass and coffee next to the book" />
          </div>
        </div>
      </div>

      <h1 class="my-4"> &</h1>

      <div class="flex flex-wrap -mx-2 mb-8 mt-8">
        <div class="w-full lg:w-1/2 px-2">
          <div class="flex justify-center text-center">
          <img class="rounded w-full sm:w-1/2 lg:w-1/2 h-auto shadow-2xl" src="~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg" alt="Book on top of a  map. A camera, magnifiying glass and coffee next to the book" />
          </div>
        </div>
        <div class="w-full md:w-1/2 lg:w-1/2 px-2 mb-4">
          <div class="text-sm text-grey-dark text-left">
              <h1>Sheila Jasmine Meutia Azzara S.Sos</h1>
              <p>Daughter of Ahmad Jani Subhan Maliki</p>
              <p>&</p>
              <p>Dwi Rosaline Febrina</p>
          </div>
        </div>
      </div>
    </section>
    <section id="main3" class="w-full p-32 bg-center text-center huhu main-3 hidden">
      <div class="our-story">
        <h1>Our Story</h1>
        <img class="rounded w-full sm:w-1/2 lg:w-1/2 h-auto shadow-2xl mx-auto" src="~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg" alt="Book on top of a  map. A camera, magnifiying glass and coffee next to the book" />
        <img class="rounded w-full sm:w-1/2 lg:w-1/2 h-auto shadow-2xl mx-auto" src="~assets/Timi Self Photo Studio Jakarta - Depok-6.jpg" alt="Book on top of a  map. A camera, magnifiying glass and coffee next to the book" />
        <p>New Years 2000</p>
        <img class="rounded w-full sm:w-1/2 lg:w-1/2 h-auto shadow-2xl mx-auto" src="~assets/Timi Self Photo Studio Jakarta - Depok.jpg" alt="Book on top of a  map. A camera, magnifiying glass and coffee next to the book" />
        <p>Rakha Love Sheila</p>
        <img class="rounded w-full sm:w-1/2 lg:w-1/2 h-auto shadow-2xl mx-auto" src="~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg" alt="Book on top of a  map. A camera, magnifiying glass and coffee next to the book" />
        <p>Ganteng Beud</p>
        <p>Ganteng Beud</p>
        <p>Ganteng Beud</p>
        <p>Ganteng Beud</p>
        <p>Ganteng Beud</p>
        <p>Rakha & Sheila</p>
      </div>
    </section>
    <section id="main4" class="w-full p-32 bg-center text-center hoho main-3 hidden">
      <div class="flex flex-wrap -mx-2 mb-8 mt-8">
        <div class="w-full lg:w-1/2 px-2">
          <div class="flex justify-center text-center">
          <img @click="toggleModal" class="rounded w-full sm:w-1/2 lg:w-1/2 h-auto shadow-2xl" src="~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg" alt="Book on top of a  map. A camera, magnifiying glass and coffee next to the book" />
          </div>
        </div>
        <div class="w-full md:w-1/2 lg:w-1/2 px-2 mb-4" style="align-self: center;">
          <div class="text-sm text-grey-dark">
              <h1>Rakha Gusti Wardhana S.Kesos</h1>
              <p>Son of Agus Wardhana S.E</p>
              <p>&</p>
              <p>Agustina S.E</p>
              <button @click="toggleModal" class="py-3 px-8 bg-gray-400 hover:bg-gray-300 text-gray-800 hover:text-gray-900 rounded-lg hover:shadow-xl transition duration-300">See details</button>
          </div>
        </div>
      </div>
    </section>

    <section class="fixed z-10 overflow-y-auto top-0 w-full left-0 hidden" id="modals">
      <div class="flex items-center justify-center min-height-100vh pt-4 px-4 pb-20 text-center sm:block sm:p-0">
        <div class="fixed inset-0 transition-opacity">
          <div class="absolute inset-0 bg-gray-900 opacity-75" />
        </div>
        <span class="hidden sm:inline-block sm:align-middle sm:h-screen">&#8203;</span>
        <div class="inline-block align-center bg-white rounded-lg text-left overflow-hidden shadow-xl transform transition-all sm:my-8 sm:align-middle sm:max-w-lg sm:w-full" role="dialog" aria-modal="true" aria-labelledby="modal-headline">
          <div class="bg-white px-4 pt-5 pb-4 sm:p-6 sm:pb-4">
            <label>Name</label>
            <input type="text" class="w-full bg-gray-100 p-2 mt-2 mb-3" />
            <label>Url</label>
            <input type="text" class="w-full bg-gray-100 p-2 mt-2 mb-3" />
          </div>
          <div class="bg-gray-200 px-4 py-3 text-right">
            <button type="button" class="py-2 px-4 bg-gray-500 text-white rounded hover:bg-gray-700 mr-2" @click="toggleModal"><i class="fas fa-times"></i> Cancel</button>
            <button type="button" class="py-2 px-4 bg-blue-500 text-white rounded hover:bg-blue-700 mr-2"><i class="fas fa-plus"></i> Create</button>
          </div>
        </div>
      </div>
    </section>

    <section id="main5" class="w-full p-32 bg-center text-center haha hidden">
      <form class="form">
        <h2>RSVP</h2>
        <div>

          <input type="text" id="name" placeholder="name" />

          <input id="yes" type="radio" name="rsvps" value="yes" /><label for="yes" class="side-label">Accepts with pleasure</label>

          <input type="radio" id="no" name="rsvps" value="no" /><label for="no" class="side-label">Declines with regrets</label>

          <div class="regrets-comments">
            <label for="box-of-regrets" class="top-label">Regrets</label><br>
            <textarea id="box-of-regrets"></textarea>
          </div>

          <div class="accept-form">
            <label for="box-of-regrets" class="top-label">Plus one?</label><br>
            <input id="plus-one" type="radio" name="plus1" value="yes" /><label for="plus-one" class="side-label">Yes</label>

            <input type="radio" id="just-me" name="plus1" value="no" /><label for="just-me" class="side-label">No</label><br>

            <!-- <input type="text" id="plus-one-name" placeholder="your guest's name" /> -->

            <div class="gift" id="plus-one-name">
            <label for="box-of-regrets" class="top-label">Do you wish to personalize your gift?</label><br>
            <input id="plus-one" type="radio" name="plus1" value="yes" /><label for="plus-one" class="side-label">Yes</label>

            <input type="radio" id="just-me" name="plus1" value="no" /><label for="just-me" class="side-label">No</label><br>
            </div>

            <div class="gift" id="just-me-hehe">
            <label for="box-of-regrets" class="top-label">Do you wish to personalize your gift?</label><br>
            <input id="plus-one" type="radio" name="plus1" value="yes" /><label for="plus-one" class="side-label">Yes</label>

            <input type="radio" id="just-me" name="plus1" value="no" /><label for="just-me" class="side-label">No</label><br>
            </div>
          </div>
        </div>
        <button type="submit" form="form" value="Submit">Submit</button>
      </form>
    </section>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      isOpen: true
    };
  },

  methods: {
    onToggle() {
      document.getElementById("modal").style.transform="translateY(-100%)";
      document.getElementById("modal").style.transition=" all 0.2s";
      document.getElementById("main").style.display="block";
      document.getElementById("main2").style.display="block";
      document.getElementById("main3").style.display="block";
      document.getElementById("main4").style.display="block";
      document.getElementById("main5").style.display="block";
    },
    toggleModal(){
      document.getElementById('modals').classList.toggle('hidden');
    }
  }
}
</script>
<style>
.bg-dunes {
  background-image: url('~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg');
  background-size: cover;
}

.bgbg {
  background-image: url('~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg');
}
.hehe {
  background-image: url('~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg');
  background-size: cover;
}

.huhu{
  background-image: url('~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg');
  background-size: cover;
}

.hoho{
  background-image: url('~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg');
  background-size: cover;
}

.haha{
  background-image: url('~assets/Timi Self Photo Studio Jakarta - Depok-4.jpg');
  background-size: cover;
}

.main-1 {
  position: relative;
}

.main-2 {
  position: absolute;
  top: 0;
}

.text-top {
  align-self: flex-start;
  font-size: 2em;
}

.animate-first-left{
  animation: fadeInLeft 1s ease-in-out;
}

.text-middle {
  align-self: center;
  font-size: 6.5em;
}

.text-bottom {
  align-self: flex-end;
  font-size: 2em;
}

.animate-first-right{
  animation: fadeInRight 1s ease-in-out;
}

@keyframes fadeInLeft {
  from {
    opacity: 0;
    transform: translateX(-100px);
  }
  to {
    opacity: 1;
  }
}

@keyframes fadeInRight {
  from {
    opacity: 0;
    transform: translateX(100px);
  }
  to {
    opacity: 1;
  }
}

*,
*::before,
*::after {
	box-sizing: border-box;
	padding: 0;
	margin: 0;
}

.haha.form {
	border: 2px solid #873b51;
	width: 40%;
	min-width: 300px;
	margin: 40px auto;
	position: relative;
}

.haha.h2 {
	font-family: 'Six Caps', sans-serif;
	font-size: 48px;
	position: absolute;
	display: block;
	background-color: #fff;
	padding: 0 10%;
	top: -30px;
	left: 35%;
}

input {
	width: 100%;
	padding: 10px;
	box-sizing: border-box;
	background: none;
	outline: none;
	resize: none;
	border: 0;
	font-family: 'Montserrat', sans-serif;
	transition: all .3s;
	border-bottom: 2px solid #873b51;
	border-left: 2px solid #873b51
}

input[type="checkbox"],
input[type="radio"] {
	position: absolute;
	visibility: hidden;
}

textarea {
	display: block;
	width: 100%;
	max-width: 100%;
	padding: 5px;
	border: 2px solid #873b51;
	color: #593e4e;
	background-color: #fff;
	font-family: inherit;
	font-size: inherit;
	margin-top: 11px;
	appearance: none;
	height: 100px;
}

textarea:focus {
	outline: 2px solid #873b51;
}

.side-label {
	display: inline-block;
	position: relative;
	margin: 20px 43px;
	padding-left: 25px;
	cursor: pointer;
}

.side-label::before,
.side-label::after {
	content: '';
	position: absolute;
	top: 0;
	left: 0;
}

.side-label::before {
	display: block;
	width: 15px;
	height: 15px;
	border: 2px solid #873b51;
}

input:focus + .side-label::before {
	border-color: #873b51;
}

.side-label:after {
	display: none;
	width: 9px;
	height: 9px;
	margin: 3px;
	background-color: #873b51;
}

input:checked + .side-label:after {
	display: block;
}

.regrets-comments {
	transition: all 1s ease-out;
	opacity: 0;
	height: 0;
	margin: 10px 0 0 35px;
	overflow: hidden;
	padding: 0;
}

.accept-form {
	transition: all 1s ease-out;
	opacity: 0;
	height: 0;
	padding: 0px 43px;
	overflow: hidden;
}

#yes:checked ~ .accept-form {
	opacity: 1;
	height: auto;
}

#no:checked ~ .regrets-comments {
	opacity: 1;
	height: auto;
}

#plus-one-name, #just-me-hehe {
	transition: opacity 1s ease-out;
	opacity: 0;
	height: 0;
}
#just-me:checked ~ #just-me-hehe{
  opacity: 1;
	height: auto;
}

#plus-one:checked ~ #plus-one-name {
	opacity: 1;
	height: auto;
}

.accept-form > label:nth-child(4) {
	margin: 20px 0px;
}

.haha>form>button {
	cursor: pointer;
	display: inline-block;
	color: #873b51;
	-webkit-appearance: none;
	border: 2px solid #873b51;
	background-color: #fff;
	padding: 10px 20px;
	font-size: 15px;
	text-transform: uppercase;
	-webkit-transform: translateZ(0);
	transform: translateZ(0);
	box-shadow: 0 0 1px rgba(0, 0, 0, 0);
	-webkit-backface-visibility: hidden;
	backface-visibility: hidden;
	-moz-osx-font-smoothing: grayscale;
	-webkit-transition-property: color;
	transition-property: color;
	-webkit-transition-duration: 0.2s;
	transition-duration: 0.2s;
}

.haha.button:before {
	content: "";
	position: absolute;
	z-index: -1;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	background: #873b51;
	-webkit-transform: scaleY(0);
	transform: scaleY(0);
	-webkit-transform-origin: 50% 100%;
	transform-origin: 50% 100%;
	-webkit-transition-property: transform;
	transition-property: transform;
	-webkit-transition-duration: 0.2s;
	transition-duration: 0.2s;
	-webkit-transition-timing-function: ease-out;
	transition-timing-function: ease-out;
}

.haha.button:hover,
.haha.button:focus,
.haha.button:active {
	color: white;
}

.haha.button:hover:before,
.haha.button:focus:before,
.haha.button:active:before {
	-webkit-transform: scaleY(1);
	transform: scaleY(1);
}
</style>
