<template>
	<div>
		<h1>Check the console of the browser and server.</h1>
		<p>Remember the varible</p>
		<p>Now change the <strong>VITE_TEST</strong> varible in .env file, save and refresh the browser window</p>
		<p>Check your terminal and browser console. The varible doesn't change</p>
	</div>
</template>

<script setup>
	console.log('VITE_TEST=' + import.meta.env.VITE_TEST)
</script>
