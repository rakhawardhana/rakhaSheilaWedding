<template>
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

            <input type="text" id="plus-one-name" placeholder="your guest's name" />

            </div>

        </div>
        <button type="submit" form="form" value="Submit">Submit</button>
    </form>
</template>
<style scoped>
*,
*::before,
*::after {
	box-sizing: border-box;
	padding: 0;
	margin: 0;
}

body {
	color: #873b51;
	font-family: 'Montserrat', sans-serif;
	font-size: 12px;
}

form {
	border: 2px solid #873b51;
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

div {
	padding: 40px;
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
	color: #873b51;
	-webkit-appearance: none;
	border: 2px solid #873b51;
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

button:hover,
button:focus,
button:active {
	color: white;
}

button:hover:before,
button:focus:before,
button:active:before {
	-webkit-transform: scaleY(1);
	transform: scaleY(1);
}
</style>