<script>
	export let withIcon = false;
	export let iconPosition = "left";
</script>

<button class="bg-blue-500 text-white w-60 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center gap-2 hover:bg-purple-500">
  {#if withIcon && iconPosition === "left"}
    <div class="w-6 h-6 border border-s-white rounded-full"></div>
  {/if}
  <span>Button</span>
  {#if withIcon && iconPosition === "right"}
    <div class="w-6 h-6 border border-s-white rounded-full"></div>
  {/if}
</button>