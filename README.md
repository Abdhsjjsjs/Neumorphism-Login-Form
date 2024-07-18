<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8" />
	<meta http-equiv="X-UA-Compatible" content="IE=edge" />
	<title>GFG Neumorphism Signin</title>
	<meta name="description" content="" />
	<meta name="viewport" content="width=device-width,
								initial-scale=1" />
	<style>
		* {
			box-sizing: border-box;
		}

		body {
			margin: 0;
			/*Display width and height*/
			height: 100vh;
			width: 100vw;
			overflow: hidden;
			font-family: "Lato", sans-serif;
			font-weight: 700;
			/* To make all the elements center */
			display: flex;
			align-items: center;
			justify-content: center;
			/*Font color and background Color*/
			color: #555;
			background: #ecf0f3;
		}

		.gfg-div {
			/* Login Card Width and height */
			width: 430px;
			height: 500px;
			/* padding */
			padding: 20px 35px 15px 35px;
			border-radius: 35px;
			background: #ecf0f3;
			/* Box-shadow for 3d visualization*/
			box-shadow: -6px -6px 6px rgba(255, 255, 255, 0.8),
				6px 6px 6px rgba(0, 0, 0, 0.2);
		}

		.gfg-logo {
			background: url("gfg-logo.png");
			background-size: cover;
			width: 100px;
			height: 100px;
			border-radius: 50%;
			margin: 0 auto;
			/* Box-shadow for logo */
			box-shadow: 0px 0px 2px #5f5f5f, 0px 0px 0px 5px #ecf0f3,
				8px 8px 15px #a7aaaf, -8px -8px 15px #ffffff;
		}

		.gfg-title {
			text-align: center;
			font-size: 28px;
			padding-top: 24px;
			letter-spacing: 0.5px;
			color: #5ed887;
		}

		.gfg-sub-title {
			text-align: center;
			font-size: 15px;
			padding-top: 7px;
			letter-spacing: 3px;
			color: #5eaa77;
		}

		.gfg-input-fields {
			width: 100%;
			padding: 20px 5px 10px 5px;
		}

		.gfg-input-fields input {
			/* To hide default browser options of input field */
			border: none;
			outline: none;
			/* Custom design for the input field */
			background: none;
			font-size: 18px;
			color: #555;
			padding: 15px 10px 15px 5px;
		}

		.gfg-email,
		.gfg-password {
			margin-bottom: 20px;
			border-radius: 20px;
			/* Box-shadow for 3d */
			box-shadow: inset 5px 5px 5px #cbced1,
				inset -5px -5px 5px #ffffff;
		}

		.gfg-input-fields svg {
			height: 22px;
			margin: 0 10px -3px 25px;
		}

		.gfg-button {
			/* To hide default browser options of input field */
			outline: none;
			border: none;
			/* Custom design for the Button */
			cursor: pointer;
			width: 100%;
			height: 60px;
			border-radius: 25px;
			font-size: 20px;
			font-weight: 700;
			font-family: "Lato", sans-serif;
			color: #fff;
			text-align: center;
			background: #67d18a;
			box-shadow: 7px 7px 8px #cbced1, -7px -7px 8px #ffffff;
			transition: 0.5s;
		}

		.gfg-button:hover {
			background: #5fb87d;
		}

		.gfg-button:active {
			background: #4a9764;
		}

		.gfg-link {
			padding-top: 20px;
			text-align: center;
		}

		.gfg-link a {
			text-decoration: none;
			color: #aaa;
			font-size: 15px;
			transition: 0.5s;
		}

		.gfg-link a:hover {
			text-decoration: none;
			color: #67d18a;
			font-size: 15px;
		}
	</style>
</head>

<body>
	<div class="gfg-div">
		<div class="gfg-logo"></div>
		<div class="gfg-title">Geeksforgeeks</div>
		<div class="gfg-sub-title">Neumorphism Login Form</div>
		<div class="gfg-input-fields">
			<div class="gfg-email">
				<svg fill="#999" viewBox="0 0 1024 1024">
					<path class="path1"
						d="M896 307.2h-819.2c-42.347 0-76.8 34.453-76.8 76.8v460.8c0
							42.349 34.453 76.8 76.8 76.8h819.2c42.349 0 76.8-34.451
							76.8-76.8v-460.8c0-42.347-34.451-76.8-76.8-76.8zM896
							358.4c1.514 0 2.99 0.158 4.434 0.411l-385.632 257.090c-14.862
							9.907-41.938 9.907-56.802 0l-385.634-257.090c1.443-0.253
							2.92-0.411 4.434-0.411h819.2zM896 870.4h-819.2c-14.115
							0-25.6-11.485-25.6-25.6v-438.566l378.4 252.267c15.925
							10.618 36.363 15.925 56.8 15.925s40.877-5.307
							56.802-15.925l378.398-252.267v438.566c0 14.115-11.485
							25.6-25.6 25.6z">
					</path>
				</svg>
				<input type="email" placeholder="email" />
			</div>
			<div class="gfg-password">
				<svg fill="#999" viewBox="0 0 1024 1024">
					<path class="path1"
						d="M742.4 409.6h-25.6v-76.8c0-127.043-103.
							357-230.4-230.4-230.4s-230.4 103.357-230.4
							230.4v76.8h-25.6c-42.347 0-76.8 34.453-76.8
							76.8v409.6c0 42.347 34.453 76.8 76.8 76.8h512c42.347
							0 76.8-34.453 76.8-76.8v-409.6c0-42.347-34.453-76.
							8-76.8-76.8zM307.2 332.8c0-98.811 80.389-179.2
							179.2-179.2s179.2 80.389 179.2 179.2v76.8h-358.4v-76.8zM768 
							896c0 14.115-11.485 25.6-25.6 25.6h-512c-14.115 0-25.6-11.
							485-25.6-25.6v-409.6c0-14.115 11.485-25.6 25.6-25.6h512c14.
							115 0 25.6 11.485 25.6 25.6v409.6z">
					</path>
				</svg>
				<input type="password"
					placeholder="password" />
			</div>
		</div>
		<button class="gfg-button">Geeksforgeeks Signin</button>
		<div class="gfg-link">
			<a href="#"> Forgot password?</a> or <a href="#">Signup</a>
		</div>
	</div>
</body>
</html>
