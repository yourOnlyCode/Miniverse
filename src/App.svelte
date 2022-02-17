

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
</div>	

<PdfViewer url='./manuscripts/1.pdf' />