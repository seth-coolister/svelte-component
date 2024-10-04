<script>
	import Button from "./Button.svelte";
</script>

<svelte:head>
	<link rel="stylesheet" href="https://unpkg.com/tailwindcss@2.2.19/dist/tailwind.min.css"/>
</svelte:head>

<main>

  <div class="flex justify-center">
    <Button state="default" iconPosition="none"/>
    <Button state="default" iconPosition="left"/>
    <Button state="default" iconPosition="right"/>
    <Button state="default" iconPosition="side"/>
  </div>
	
  <div class="flex justify-center">
    <Button state="pressed" iconPosition="none"/>
    <Button state="pressed" iconPosition="left"/>
    <Button state="pressed" iconPosition="right"/>
    <Button state="pressed" iconPosition="side"/>
  </div>

  <div class="flex justify-center">
    <Button state="disabled" iconPosition="none"/>
    <Button state="disabled" iconPosition="left"/>
    <Button state="disabled" iconPosition="right"/>
    <Button state="disabled" iconPosition="side"/>
  </div>

</main>

