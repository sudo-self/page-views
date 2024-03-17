<script>

  export let data
  function refreshPage() {
  location.reload()
  }
  import Time, { svelteTime } from "svelte-time";
	import { dayjs } from "svelte-time";
	let time = dayjs().format('MMM DD, YYYY');

</script>

<main class="relative flex flex-col items-center justify-center min-h-screen py-10">
  <a href="https://random-react.vercel.app/"
    class="px-6 py-2 text-sm font-medium text-green-700 transition-all rounded-full shadow-sm bg-white/30 dark:bg-white/80 ring-1 ring-green-700/5 dark:text-green hover:shadow-lg active:shadow-sm hover:text-emerald-700">
    ENTER
  </a>
</main>
  <h1
    class="pt-4 pb-8 bg-gradient-to-br dark:from-white from-black via-[#707070] to-[#ffffff] bg-clip-text text-center text-4xl font-medium tracking-tight text-transparent md:text-7xl bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 opacity-0 transition duration-300 ease-in-out hover:opacity-70
  >
JesseJesse.com
  </h1>
  </h1>
  <div
    class="flex flex-col items-center w-full max-w-xl p-12 mx-auto rounded-lg shadow-xl dark:bg-white/10 bg-white/30 ring-1 ring-gray-900/5 backdrop-blur-lg"
  >
    <div class="mb-6 text-lg text-center">
  
    
    </div>
    <button
      on:click={refreshPage}
      class="mb-6 font-bold underline opacity-70 hover:opacity-100"
    >
     Refresh Page
    </button>
    <div class="text-5xl font-bold">
      {data?.pageVisits}
    </div>
  </div>
  <div
    class="w-full max-w-lg mt-6 font-light text-center text-gray-600 dark:text-gray-300"
  >
    ETH: 0x097e0dda06abc2ecfac77f4af56eecc5a80cb68f
    <a
      href="https://rarible.com/token/0xc9154424b823b10579895ccbe442d41b9abd96ed:4293533968084887940418635492547144507113596156710918506364799290880552861698"
      class="font-medium underline transition-colors underline-offset-4 dark:hover:text-white hover:text-black"
    >
     NFT
    </a>
    <div class="flex items-center justify-center my-2">
      <span>Built with&nbsp;&#10084;&nbsp;</span>
      <a
        href="https://openai-ufo.vercel.app"
        class="flex items-center font-medium underline transition-colors underline-offset-4 dark:hover:text-white hover:text-black"
      >
        <img src="svelte_logo.png" alt="svelte logo" class="h-6 mx-2" />
        <p>Open Ai Chat</p>
      </a>
      .
    </div>
  </div>
  <div class="flex flex-col grow">
    <a href="https://openai-ufo.vercel.app">
      <img
        src="/vercel.svg"
        alt="Vercel Logo"
        class="my-2 text-white dark:text-white"
        width={100}
        height={24}
      />
    </a>
    <a
      href="https://sudo-self.github.io/rustbook/"
      class="flex items-center h-8 mt-auto space-x-2 bottom-20 right-20"
    >
      <img src="/github.svg" alt="GitHub Logo" class="h-6 dark:invert" />
      <p class="font-light">sudo-self.github.io/</p>
    </a>
  </div>
</main>



