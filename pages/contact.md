---
layout: single
permalink: /contact/
title: Contact
author_profile: true
classes: wide
date: December 28, 2022
---

Email: [mchinmayee-at-proton.me](mailto:mchinmayee@proton.me)

<html>

<head>
	<style>
		body {
			/* margin: 100px; */
		}

		#textbox {
			width: 40vw;
			height: 30vh;
			position: absolute;
			margin-left: 50px;
			margin-top: 20px;
		}

		button {
			<!-- width: 70px;
			height: 40px; -->
			margin-top: 120px;
			margin-left: 50px;
			background-color: #30e3ca;
			color: white;
			border-radius: 10px;
			box-shadow: grey;
			position: absolute;
		}

		#sample {
			width: 70vw;
			margin: 50px;
			background-color: green;
			color: white;
			padding: 20px;
			font-size: x-large;
			position: absolute;
		}

		h1 {
			margin-left: 50px;
			margin-top: 160px;
		}
	</style>
</head>

<body>
	
	<button onclick="copyText()">Copy Email ID</button>
	<br />
	
	<!-- <h1>Copied Text:</h1><br />
	<textarea id="textbox"></textarea> -->
	
	<script>
		function copyText() {
	
			/* Copy text into clipboard */
			navigator.clipboard.writeText
				("mchinmayee@proton.me");
		}
	</script>
</body>

</html>
