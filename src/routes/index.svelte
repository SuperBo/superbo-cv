<script>
  import '../app.css';
  import { Cookie, Linkedin, Github } from 'lucide-svelte'

  import About from '$lib/About.svelte'
  import Resume from '$lib/Resume.svelte'

  import profile from '$lib/assets/profile.webp';
</script>

<!--
<h1>Welcome To SuperBo's CV</h1>
<p>Visit <span class="text-3xl">Super</span> <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
-->

<div class="grid grid-cols-4 font-poppins bg-sky-400 xl:w-4/6 lg:w-5/6 w-full mx-auto rounded-[32px] shadow-xl">
  <div class="hidden lg:flex flex-col items-center text-white mt-20">
    <img
      class="w-2/3 rounded-full border-4 border-white my-6"
      src={profile} alt="Super Bo Picture"
    />
    <p class="text-white font-semibold text-4xl text-center leading-5 mb-3">Y Nguyen</p>
    <p class="text-white font-light text-lg text-center my-2">Machine Learning Engineer</p>
    <ul class="flex flex-row gap-5 my-2">
      <li><a href="https://www.linkedin.com/in/y-h-nguyen"><Linkedin size=28 strokeWidth=1.2/></a></li>
      <li><a href="https://github.com/SuperBo"><Github size=28 strokeWidth=1.2/></a></li>
      <li><a href="https://superbo.dev"><Cookie size=28 strokeWidth=1.2/></a></li>
    </ul>
  </div>
  <div class="bg-white col-span-4 lg:col-span-3 p-14 font-normal text-light text-slate-700 rounded-[32px] lg:rounded-l-none">
    <About/>
    <Resume/>
  </div>
</div>
