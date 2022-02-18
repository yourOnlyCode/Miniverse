


<script>
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
		<h2 class="disclaimer">public login unavailable</h2>
	</div>
</div>	

<div class="box-container">
	<h3 class="box">MATTY's BOX</h3>
</div>

<PdfViewer url='./manuscripts/1.pdf' />
