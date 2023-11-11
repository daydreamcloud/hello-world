# hello-world
<svg fill="none" viewBox="0 0 1200 300" width="1200" height="300" xmlns="http://www.w3.org/2000/svg">
		<foreignObject width="100%" height="100%">
			<div xmlns="http://www.w3.org/1999/xhtml">
				<style>
					@keyframes rotate {
						0% {
							transform: rotate(3deg);
						}
						100% {
							transform: rotate(-3deg);
						}
					}
					@keyframes gradientBackground {
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
					@keyframes fadeIn {
						0% {
							opacity: 0;
						}
						66% {
							opacity: 0;
						}
						100% {
							opacity: 1;
						}
					}
					.container {
						font-family:
							system-ui,
							-apple-system,
							'Segoe UI',
							Roboto,
							Helvetica,
							Arial,
							sans-serif,
							'Apple Color Emoji',
							'Segoe UI Emoji';
						display: flex;
						flex-direction: column;
						align-items: center;
						justify-content: center;
						margin: 0;
						width: 100%;
						height: 300px;
					/*	background: linear-gradient(-45deg, #ff8aa2, #b5c2ff, #a0fffc); */
						background-size: 600% 400%;
						animation: gradientBackground 10s ease infinite;
						border-radius: 10px;
						color: rgb(224, 224, 224);
						text-align: center;
					}
					h1 {
						font-size: 50px;
						line-height: 1.3;
						letter-spacing: 5px;
						text-transform: uppercase;
						text-shadow:
							0 1px 0 #cacaca,
							0 2px 0 #cacaca,
							0 3px 0 #cacaca,
							0 4px 0 #cacaca,
							0 12px 5px rgba(0, 0, 0, 0.1);
						animation: rotate ease-in-out 1s infinite alternate;
					}
					p {
            					color: #828282;
						font-size: 20px;
						letter-spacing: 1px;
						text-shadow: 0 1px 0 #cacaca;
						animation: 5s ease 0s normal forwards 1 fadeIn;
					}
				</style>
				<div class="container">
					<h1>Welcome to<br/>my world</h1>
					<p>Let's try things out</p>
				</div>
			</div>
		</foreignObject>
	</svg>
