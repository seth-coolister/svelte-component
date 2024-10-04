<script>
  export let iconPosition = "left";
  export let state = "default";
</script>

<div>
  {#if state === "default" && iconPosition === "none"}
    <button class="bg-purple-500 text-white w-80 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center">
      <span>Button</span>
    </button>
  {/if}
  {#if state === "default" && iconPosition === "left"}
    <button class="bg-purple-500 text-white w-80 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center">
      <span>Button</span>
      <div class="absolute left-4 w-6 h-6 border-2 rounded-full"></div>
    </button>
  {/if}
  {#if state === "default" && iconPosition === "right"}
    <button class="bg-purple-500 text-white w-80 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center">
      <span>Button</span>
      <div class="absolute right-4 w-6 h-6 border-2 rounded-full"></div>
    </button>
  {/if}
  {#if state === "default" && iconPosition === "side"}
    <button class="bg-purple-500 text-white w-80 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center">
      <span>Button</span>
      <div class="ml-2 w-6 h-6 border-2 rounded-full"></div>
    </button>
  {/if}

  {#if state === "pressed" && iconPosition === "none"}
    <button class="bg-purple-700 text-white w-80 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center">
      <span>Button</span>
    </button>
  {/if}
  {#if state === "pressed" && iconPosition === "left"}
    <button class="bg-purple-700 text-white w-80 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center">
      <span>Button</span>
      <div class="absolute left-4 w-6 h-6 border-2 rounded-full"></div>
    </button>
  {/if}
  {#if state === "pressed" && iconPosition === "right"}
    <button class="bg-purple-700 text-white w-80 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center">
      <span>Button</span>
      <div class="absolute right-4 w-6 h-6 border-2 rounded-full"></div>
    </button>
  {/if}
  {#if state === "pressed" && iconPosition === "side"}
    <button class="bg-purple-700 text-white w-80 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center">
      <span>Button</span>
      <div class="ml-2 w-6 h-6 border-2 rounded-full"></div>
    </button>
  {/if}

  {#if state === "disabled" && iconPosition === "none"}
    <button class="bg-gray-500 text-white w-80 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center">
      <span class="text-gray-300">Button</span>
    </button>
  {/if}
  {#if state === "disabled" && iconPosition === "left"}
    <button class="bg-gray-500 text-white w-80 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center">
      <span class="text-gray-300">Button</span>
      <div class="absolute left-4 w-6 h-6 border-2 border-gray-300 rounded-full"></div>
    </button>
  {/if}
  {#if state === "disabled" && iconPosition === "right"}
    <button class="bg-gray-500 text-white w-80 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center">
      <span class="text-gray-300">Button</span>
      <div class="absolute right-4 w-6 h-6 border-2 border-gray-300 rounded-full"></div>
    </button>
  {/if}
  {#if state === "disabled" && iconPosition === "side"}
    <button class="bg-gray-500 text-white w-80 h-12 rounded-full relative ml-4 mt-6 flex justify-center items-center">
      <span class="text-gray-300">Button</span>
      <div class="ml-2 w-6 h-6 border-2 border-gray-300 rounded-full"></div>
    </button>
  {/if}
</div>