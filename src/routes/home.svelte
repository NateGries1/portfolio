<section class="container">
	<div class="content">
		<div class="info">
			<h1 class="title">Nate Gries</h1>
			<h4 class="subtitle">
				Delivering efficient solutions through the art of algorithms and data structures.
			</h4>
			<p class="description">
				Welcome to my website! My name is Nate and I am an aspiring Software Engineer with a passion
				for algorithms and data structures.
			</p>
		</div>
		<div class="img-container">
			<img src="image.jpg" alt="Avatar of Nate Gries" />
		</div>
	</div>
</section>

<style>
	.container {
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;
		height: 100vh;
		margin: 0 auto;
		background-image: url('background.png');
	}

	.content {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		width: 80%;
	}

	.info {
		width: 50%;
		margin: 0;
		display: flex;
		flex-direction: column;
		justify-content: center;
	}

	.title {
		font-size: 90px;
		font-weight: 400;
		padding: 0;
		margin: 0;
	}

	.subtitle {
		font-size: 14px;
		font-weight: 100;
		margin: 0;
		padding: 0;
	}

	.description {
		margin-top: 0.5rem;
		/* text-align: justify; */
		font-weight: 300;
		font-size: 24px;
	}

	.img-container {
		width: 50%;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	img {
		width: 250px;
		height: 250px;
		border-radius: 100%;
		margin: auto;
	}

	@media (max-width: 768px) {
		.content {
			flex-direction: column;
		}

		.info {
			width: 80%;
			margin: 0 auto;
		}

		.title {
			font-size: 60px;
			text-align: center;
		}

		.subtitle {
			text-align: center;
		}

		.description {
			text-align: center;
			font-size: 18px;
		}

		.img-container {
			width: 100%;
		}

		img {
			width: 200px;
			height: 200px;
		}
	}
</style>
