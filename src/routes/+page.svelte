<script>
	import Home from './home.svelte';
	import About from './about.svelte';
	import Projects from './projects.svelte';
	import Contact from './contact.svelte';
	import Skills from './skills.svelte';
</script>

<svelte:head>
	<title>Nate's Porfolio</title>
</svelte:head>

<div id="home">
	<Home />
</div>

<div id="about">
	<About />
</div>

<div id="projects">
	<Projects />
</div>

<div id="skills">
	<Skills />
</div>

<div id="contact">
	<Contact />
</div>
