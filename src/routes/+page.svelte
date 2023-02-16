<script>

</script>

<svelte:head>
	<title>Conduit</title>
</svelte:head>

<div>
		<h1>Rejoignez la communauté de cinéphiles voyageurs!
			<button onclick="window.location.href = '/locations';">Découvrir les lieux de tournage de vos films préférés</button>
		</h1>
		<body>
		<img src="https://dynamic-media-cdn.tripadvisor.com/media/photo-o/21/65/a6/50/caption.jpg?w=1200&h=-1&s=1&cx=1385&cy=866&chk=v1_b56719399b629581897d">

		</body>

</div>


<style>
	h1 {
		margin: 3.5em 0;
		text-align: center;
	}

	body{
		background-color: #f2d689;
		z-index: 1;
	}
	h1 {
		text-shadow: 2px 1px #381506 ;
		color: #12251d;
	}
	img {
		opacity: 0.5;
		in-height: 100%;
		min-width: 1024px;
		width: 100%;
		height: auto;
		position: fixed;
		top: 0;
		z-index: -1;
	}
	button{
		display: inline-block;
		background-color: #381506;
		border-radius: 10px;
		border: 4px  #cccccc;
		color: #eeeeee;
		text-align: center;
		font-size: 16px;
		width: 400px;
		transition: all 0.5s;
		cursor: context-menu;
		margin: 65px;
		padding: 15px;
	}

	button:hover {
		background-color: green;
	}
	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

