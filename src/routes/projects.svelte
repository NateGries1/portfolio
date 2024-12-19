<section class="container">
	<div class="content">
		<h1 class="header">PROJECTS</h1>
		<div class="groups">
			<a href="https://github.com/NateGries1/lcpilot" class="project-link" target="_blank">
				<div class="project">
					<img src="lcpilot.png" alt="Screenshot of project acmcsuf.com" />
					<div class="description">
						<h4 class="title">LCPilot</h4>
						<div class="tech-list">
							<p class="tech">Next.js</p>
							<p class="tech">TypeScript</p>
							<p class="tech">Firebase</p>
						</div>
					</div>
				</div>
			</a>

			<a href="https://github.com/NateGries1/WikiGuess" class="project-link" target="_blank">
				<div class="project">
					<img src="wikiguess.png" alt="Screenshot of project wikiguess" />
					<div class="description">
						<h4 class="title">WikiGuess</h4>
						<div class="tech-list">
							<p class="tech">Flask</p>
							<p class="tech">JavaScript</p>
							<p class="tech">React</p>
						</div>
					</div>
				</div>
			</a>

			<a href="https://github.com/NateGries1/KnightsvGnomes" class="project-link" target="_blank">
				<div class="project">
					<img src="gnome.png" alt="Screenshot of gnome asset" />
					<div class="description">
						<h4 class="title">Knights vs Gnomes</h4>
						<div class="tech-list">
							<p class="tech">Unity</p>
							<p class="tech">C#</p>
							<p class="tech">Aseprite</p>
						</div>
					</div>
				</div>
			</a>
		</div>
	</div>
	<div class="extra">
		<a href="https://github.com/NateGries1" target="_blank" class="more-projects"
			>More Projects Here</a
		>
	</div>
</section>

<style>
	.container {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		width: 50%;
		margin: 0 auto;
		min-height: 100vh;
	}

	.content {
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: center;
	}

	.groups {
		display: grid;
		grid-template-columns: 1fr 1fr;
		grid-gap: 2rem;
	}

	.project {
		border: 1px solid;
		border-radius: 25px;
		padding: 2rem;
		width: min(60vw, 400px);
		height: min(60vw, 400px);
		display: flex;
		justify-content: center;
		position: relative;
		transition:
			transform 0.2s ease,
			box-shadow 0.2s ease;
	}

	.project:hover {
		transform: scale(1.05);
		box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
	}

	.project img {
		margin-top: -2rem;
		max-width: 100%;
		height: 100%;
	}

	.project-link {
		text-decoration: none;
		color: inherit;
	}

	.description {
		position: absolute;
		bottom: 1rem;
		left: 1rem;
		padding: 0.5rem;
		border-radius: 8px;
	}

	.title {
		font-size: 20px;
		margin: 0;
		margin-bottom: 0.5rem;
	}

	.tech-list {
		display: flex;
		flex-direction: row;
	}

	.tech {
		margin: 0 0.25rem;
		border: 1px solid white;
		padding: 0.25rem 0.5rem;
		border-radius: 100px;
		font-size: 14px;
	}

	.extra {
		display: flex;
		align-items: center;
		justify-content: center;
		margin-top: 2rem;
	}

	.more-projects {
		text-decoration: none;
		color: inherit;
		font-size: 16px;
		font-weight: 600;
		border: 1px solid white;
		border-radius: 100px;
		padding: 0.5rem 1rem;
	}

	.more-projects:hover {
		background-color: rgb(73, 73, 73);
	}

	@media (max-width: 1024px) {
		.groups {
			grid-template-columns: 1fr;
		}
	}
</style>
