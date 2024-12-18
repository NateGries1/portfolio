<script>
	let activeTab = 'languages';
	const languages = ['C++', 'C#', 'Python', 'JavaScript', 'HTML/CSS', 'SQL', 'TypeScript'];
	const tools = [
		'Git/Github',
		'Unity',
		'Unreal Engine 5',
		'Firebase',
		'WSL Linux',
		'Anaconda',
		'XCode',
		'Supabase',
		'Figma'
	];
</script>

<section class="container">
	<div class="content">
		<h1 class="title">SKILLS</h1>
		<div class="tabs">
			<button
				class="tab-button"
				on:click={() => (activeTab = 'languages')}
				class:active={activeTab === 'languages'}
			>
				Languages
			</button>
			<button
				class="tab-button"
				on:click={() => (activeTab = 'tools')}
				class:active={activeTab === 'tools'}
			>
				Tools
			</button>
		</div>

		<!-- Content Display -->
		<div class="tab-content">
			{#if activeTab === 'languages'}
				{#each languages as lang}
					<div class="skill-item">{lang}</div>
				{/each}
			{:else if activeTab === 'tools'}
				{#each tools as tool}
					<div class="skill-item">{tool}</div>
				{/each}
			{/if}
		</div>
	</div>
</section>

<!-- Styles -->
<style>
	.container {
		height: 100vh;
		margin: 0 auto;
		display: flex;
		flex-direction: row;
		justify-content: center;
	}

	.content {
		margin-top: 10%;
		display: flex;
		flex-direction: column;
		/* align-items: center; */
		width: 60%;
	}
	.tabs {
		display: flex;
		justify-content: flex-start;
		gap: 1rem;
		margin-bottom: 1rem;
		width: 100%;
	}

	.tab-button {
		padding: 0.5rem 1rem;
		border: none;
		background-color: transparent;
		color: gray;
		cursor: pointer;
		border-radius: 1000px;
		transition: background-color 0.3s ease;
	}

	.tab-button.active {
		background-color: none;
		border: 1px solid white;
		color: white;
	}

	.tab-content {
		display: flex;
		/* justify-content: center; */
		flex-wrap: wrap;
		gap: 0.5rem;
	}

	.skill-item {
		width: calc(50% - 3rem);
		padding: 0.5rem 1rem;
		background-color: #353535;
		margin: 0;
	}

	@media (max-width: 768px) {
		.content {
			width: 80%;
		}

		.skill-item {
			width: 100%;
		}
	}
</style>
