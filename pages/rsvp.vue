<template>
<section>
<div id="head" class="sticky">
                
<nav class="flex py-3 items-center h-16">
    <div class="flex-1 flex items-center justify-center ">
        <nuxt-link to="/" class="no-underline global-transition text-center cursor-pointer border-b hover:border-primary border-transparent border-solid text-body1 sm:text-body2 text-primary hidden sm:inline mx-3" data-modal-toggle="treatments">
            Rakha & Sheila
        </nuxt-link>
    </div>
</nav>
            </div>
<section class="bg-red-200 text-white relative">
<!--     <div class="min-h-screen hero-image bg-center bg-cover flex" style="background-image: url(https://images.unsplash.com/photo-1491438590914-bc09fcaaf77a?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=400&fit=max&ixid=eyJhcHBfaWQiOjE0NTg5fQ);"> -->

  <!-- <div class="min-h-screen hero-image bg-right-bottom bg-cover flex" style="background-image: url(https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixlib=rb-1.2.1&q=85&fm=jpg&crop=entropy&cs=srgb&ixid=eyJhcHBfaWQiOjE0NTg5fQ);"> -->
    <!-- <div class="relative mx-auto p-4 z-10"> -->
		<div id="modal" class="relative main-2 h-screen w-full flex items-center justify-center text-center bg-cover bg-center" >
    <div class="absolute top-0 right-0 bottom-0 left-0 bg-gray-800 opacity-75"></div>
      <form class="form w-full">
        <h2 class="text-black">RSVP</h2>
        <div class="body-rsvp">

            <input type="text" id="name" placeholder="name" />

            <input id="yes" type="radio" name="rsvps" value="yes" /><label for="yes" class="side-label">Ya, saya akan hadir</label>

            <input type="radio" id="no" name="rsvps" value="no" /><label for="no" class="side-label">Mohon maaf belum bisa hadir</label>

            <div class="accept-form">
            <label for="box-of-regrets" class="top-label">Jumlah orang yang akan hadir:</label><br>
            	<input id="plus-one" type="radio" name="plus1" value="yes" />
				<label for="plus-one" class="side-label">1 orang</label>


            	<input type="radio" id="just-me" name="plus1" value="no" />
				<label for="just-me" class="side-label">2 orang</label><br>

            </div>

        </div>
        <button class="text-black" type="submit" form="form" value="Submit">Submit</button>
    </form>
    </div>
  <!-- </div> -->
</section>
</section>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lato&display=swap');

*,
*::before,
*::after {
	box-sizing: border-box;
	padding: 0;
	margin: 0;
	font-family: 'Lato';
}
#modal{
  background-image: url('~assets/_Self_Photo_Studio_Jakarta_-_Depok-2.webp');
}
#main{
  background-image: linear-gradient(180deg, #B3DEEF, #E6E6FA);
}
#head{
	background: #E6E6FA;
}

body {
	color: #873b51;
	font-family: 'Montserrat', sans-serif;
	font-size: 12px;
}

form {
	border: 2px solid #B3DEEF;
	width: 40%;
	min-width: 300px;
	margin: 40px auto;
	position: relative;
}

h2 {
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
	border-bottom: 2px solid #B3DEEF;
	border-left: 2px solid #B3DEEF;
	@media (max-width: 500px) {
		width: 40%		
	}
}
#name{
	width: 100% !important;
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
	border: 2px solid #B3DEEF;
	color: #593e4e;
	background-color: #fff;
	font-family: inherit;
	font-size: inherit;
	margin-top: 11px;
	appearance: none;
	height: 100px;
}

textarea:focus {
	outline: 2px solid #B3DEEF;
}
.body-rsvp {
	padding: 40px;
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
	border: 2px solid #B3DEEF;
}

input:focus + .side-label::before {
	border-color: #B3DEEF;
}

.side-label:after {
	display: none;
	width: 9px;
	height: 9px;
	margin: 3px;
	background-color: #B3DEEF;
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

#plus-one-name {
	transition: opacity 1s ease-out;
	opacity: 0;
	height: 0;
}

#plus-one:checked ~ #plus-one-name {
	opacity: 1;
	height: auto;
}

.accept-form > label:nth-child(4) {
	margin: 20px 0px;
}

button {
	cursor: pointer;
	display: inline-block;
	color: #000;
	-webkit-appearance: none;
	border: 2px solid #B3DEEF;
	background-color: #fff;
	padding: 10px 20px;
	font-size: 15px;
	text-transform: uppercase;
	position: absolute;
	bottom: -23px;
	right: 35px;
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

button:before {
	content: "";
	position: absolute;
	z-index: -1;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	background: #B3DEEF;
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

button:hover,
button:focus,
button:active {
	color: #000;
}

button:hover:before,
button:focus:before,
button:active:before {
	-webkit-transform: scaleY(1);
	transform: scaleY(1);
}
</style>