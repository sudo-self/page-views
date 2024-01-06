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
  <a href="https://sudo-self.vercel.app/"
    class="px-6 py-2 text-sm font-medium text-gray-600 transition-all rounded-full shadow-sm bg-white/30 dark:bg-white/80 ring-1 ring-gray-900/5 dark:text-black hover:shadow-lg active:shadow-sm hover:text-emerald-700">
    ENTER
  </a>
</main>
  <h1
    class="pt-4 pb-8 bg-gradient-to-br dark:from-white from-black via-[#707070] to-[#ffffff] bg-clip-text text-center text-4xl font-medium tracking-tight text-transparent md:text-7xl bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 opacity-0 transition duration-300 ease-in-out hover:opacity-70
  >
JesseJesse.com
  </h1>
  <div
    class="flex flex-col items-center w-full max-w-xl p-12 mx-auto rounded-lg shadow-xl dark:bg-white/10 bg-white/30 ring-1 ring-gray-900/5 backdrop-blur-lg"
  >
    <div class="mb-6 text-lg text-center">
ᗧ···ᗣ···ᗣ····♥···ᗣ····
</div>                
    <button           
      on:click={refreshPage}
      class="mb-6 font-bold underline opacity-70 hover:opacity-100"
    >     
    </button>
    <div class="text-5xl font-bold">
      {data?.pageVisits}
    </div>
<br>
    <div class="flex items-center justify-center my-2">
      <span><a href="https://openai-ufo.vercel.app"><pre>OpenAi +Svelte Vercel Tailwind</pre></a></span>
  </div>
</div>

  <div
    class="w-full max-w-lg mt-6 font-light text-center text-gray-600 dark:text-gray-300"
  >
 <br>
  <div class="flex flex-col grow">

    <a
      href="https://webdev.jessejesse.com/"
      class="flex justify-center h-6 mt-auto space-x-2 bottom-20"
    >   
     <br>     <br>
     <br>
    <img src="/github.svg" alt="GitHub Logo" class="h-6 dark:invert" /><div class="flex items-center justify-center my-2">/sudo-self&nbsp;&#169;2024</a>
  </div>
<time
  use:svelteTime="{{
    relative: true,
    timestamp: "2021-02-02",
  }}"
/></main>



