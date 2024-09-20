<script>
	import Button from "./Button.svelte";
</script>

<svelte:head>
	<link rel="stylesheet" href="https://unpkg.com/tailwindcss@2.2.19/dist/tailwind.min.css"/>
</svelte:head>

<main class="flex justify-center">

  <Button/>
  <Button withIcon={true} iconPosition="left"/>
  <Button withIcon={true} iconPosition="right"/>
  <Button withIcon={true}/>
	
</main>

