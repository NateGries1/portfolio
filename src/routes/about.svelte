<section class="container">
	<div class="content">
		<h1 class="title">ABOUT ME</h1>
		<p class="description">
			My name is Nate, short for Nathanel Gries, and I am a senior at California State University,
			Fullerton pursuing a Bachelor of Science in Computer Science. I currently serve as the
			Algorithm Team Lead for the Association for Computing Machinery (ACM) chapter at CSUF, where
			my academic focus and passion lie in advanced algorithms and data structures, as I enjoy
			tackling optimization problems and exploring efficient solutions. Proficient in C++ and
			Python, I enjoy challenging myself with competitions such as ICPC and leetcode. Outside of
			academics, I have a strong love for sports and games. I am currently looking towards getting
			into the field as an aspiring Software Engineer.
		</p>
		<div class="resume-border">
			<a href="resume.pdf" target="_blank" rel="noopener noreferrer" class="resume">Resume</a>
		</div>
	</div>
</section>

<style>
	.container {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		width: 50%;
		height: 100vh;
		margin: 0 auto;
	}

	.title {
		font-size: 1.5rem;
		margin: 0;
		padding: 0;
	}

	.description {
		margin-top: 0.5rem;
		text-align: justify;
	}

	.resume {
		display: block;
		text-decoration: none;
		color: white;
		padding: 0.5rem 1rem;
	}

	.resume-border {
		display: inline-block;
		border: 1px solid white;
		border-radius: 1000px;
	}

	@media (max-width: 768px) {
		.container {
			width: 80%;
		}
	}
</style>
