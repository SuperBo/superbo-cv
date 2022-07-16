<script>
  import { Truck, ChefHat, Cookie, Train, Linkedin, Github } from 'lucide-svelte'
</script>

<h1 class="text-4xl font-semibold">About <span class="text-sky-400">Me</span></h1>
<div class="flex flex-row gap-x-10 my-10">
  <div id="about-text" class="basis-3/5 text-base">
    I am kindly an engineer who has interests in parallel and distributed computing. I even did research in the past and got a PhD scholarship in USA. However, I wasn't able to get fit to PhD life at that time so I became a PhD drop-out now.
    Currently, I am working as a Machine Learning Engineer, enjoys dealing with challenges related to model building, features operation and model serving. 
  </div>
  <div id="info-list" class="grow">
    <ul class="space-y-1 mb-2">
      <li><span class="font-semibold text-sky-400">Residence</span> 🇻🇳 Vietnam</li>
      <li><span class="font-semibold text-sky-400">Address</span> District 2, Ho Chi Minh City</li>
      <li><span class="font-semibold text-sky-400">Email</span> @ <a href="mailto:supernbo@gmail.com">supernbo@gmail.com</a></li>
      <li><span class="font-semibold text-sky-400">Phone</span> +84 932008373</li>
    </ul>
    <ul class="flex items-center gap-x-4">
      <li class="text-sky-400"><a href="https://www.linkedin.com/in/y-h-nguyen"><Linkedin size=24/></a></li>
      <li class="text-sky-400"><a href="https://github.com/SuperBo"><Github size=24/></a></li>
      <li class="text-sky-400"><a href="https://superbo.dev"><Cookie size=24/></a></li>
    </ul>
  </div>
</div>

<!-- What I Do -->
<h2 class="text-2xl">What <span class="text-sky-400">I Do</span></h2>
<div class="my-5 grid grid-cols-2 gap-5">
  <div class="col-start-1">
    <Truck class="stroke-sky-400 stroke-1" size=40/>
    <h2 class="font-semibold text-lg my-2">Features Operation</h2>
    <p>
      Develops and maintains pipelines for features extraction, features transformation and features monitor.
    </p>
  </div>
  <div class="col-start-2 ">
    <ChefHat class="stroke-sky-400 stroke-1" size=40/>
    <h2 class="font-semibold text-lg my-2">Features Engineering</h2>
    <p>
      Finds and extracts meaningful features for model building. Explores, cleans and analyses data sometimes. 
    </p>
  </div>
  <div class="col-start-1">
    <Train class="stroke-sky-400 stroke-1" size=40/>
    <h2 class="font-semibold text-lg my-2">Model Building</h2>
    <p>
      Trains and deploys machine learning, AI models. 
    </p>
  </div>
</div>
