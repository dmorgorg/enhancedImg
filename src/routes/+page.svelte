<script>
	const pictures = import.meta.glob('./images/*.{avif,gif,heif,jpeg,jpg,png,tiff,webp}', {
		query: { enhanced: true }
	});

	console.log(pictures);
</script>

<enhanced:img src="./images/2022-08-04-042944.jpg" alt="1" />

<enhanced:img src="./images/2022-08-04-044035.jpg" alt="2" />

<style>
	img {
		width: 100%;
		height: auto;
		/* width: auto;
		height: 100%; */
	}
</style>
