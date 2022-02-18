

<script context="module">

	export const prerender = true

	import PdfViewer from 'svelte-pdf';
	let title = 'MINIVERSE'

</script>

<div class="header-container">
	<div class="logo-container">
		<img class="logo" src="favicon.png" alt="globe"/>
	</div>

	<div class="title-container">
		<h1 class="title">{title}</h1>
	</div>

	<div class="disclaimer-container">
		<h2 class="disclaimer">
			<a>LOGIN</a>
			<div id="openModal" class="modalDialog">
			<div class="popup-container">
				<a href="#close" style="color:black" title="Close" class="close">X</a>
				<p style="color:black">Login not yet available for public.</p>
				<p style="color:black">Get notified for public launch:</p>

				<!-- <label for="email">Email</label>
				<input type="text" placeholder="Enter Email" name="email" required>

				<div class="clearfix">
					<button type="submit" class="signupbtn">Sign Up</button>
				</div> -->

				<!-- "/static/netlify-form-helper.html" -->
				<form name="test" netlify netlify-honeypot="bot-field" hidden>
					<input type="text" name="name" />
					<input type="email" name="email" />
				</form>

				<!--Svelte form component-->
				<form name="contact" method="POST" data-netlify="true">
					<p>
					  <label>Your Name: <input type="text" name="name" /></label>   
					</p>
					<p>
					  <label>Your Email: <input type="email" name="email" /></label>
					</p>
					<p>
					  <button type="submit">Send</button>
					</p>
				</form>

			</div>
			</div>
		</h2>
	</div>

</div>	

<div class="box-container">
	<h3 class="box">MATTY's BOX</h3>
</div>

<PdfViewer url='./manuscripts/1.pdf' />