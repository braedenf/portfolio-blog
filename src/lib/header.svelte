<script>
    let show = false;
</script>

<nav class="flex items-center justify-between flex-wrap bg-indigo-900 p-6">
    <div class="flex items-center flex-shrink-0 text-white mr-6">
      <span class="font-semibold text-xl tracking-tight">Braeden Foster</span>
    </div>
    <div class="block md:hidden">
      <button on:click={() => show = !show} class="flex items-center px-3 py-2 border rounded text-gray-100 border-gray-200 hover:text-white hover:border-white">
        <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
      </button>
    </div>
    <div on:click={() => show = !show} class="{show ? 'block' : 'hidden'} w-full block flex-grow md:flex md:justify-end md:w-auto">
      <div>
        <a href="/" class="block md:inline-block text-sm px-4 py-2 leading-none rounded text-white border-white hover:border-transparent hover:text-teal-500 hover:bg-indigo-500 mt-4 md:mt-0">Home</a>
         <a href="/blog" class="block md:inline-block text-sm px-4 py-2 leading-none rounded text-white border-white hover:border-transparent hover:text-teal-500 hover:bg-indigo-500 mt-4 md:mt-0">Blog</a>
         <a href="/about" class="block md:inline-block text-sm px-4 py-2 leading-none rounded text-white border-white hover:border-transparent hover:text-teal-500 hover:bg-indigo-500 mt-4 md:mt-0">About</a>
      </div>
    </div>
</nav>