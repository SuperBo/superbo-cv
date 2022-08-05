<script>
  import { Tag } from 'lucide-svelte';

  let skills = [
    {name: 'C/C++', percent: 60},
    {name: 'Java', percent: 70},
    {name: 'Python', percent: 90},
    {name: 'SQL', percent: 90},
    {name: 'Scala', percent: 80},
  ];

  let knowledges = [
    'Airflow',
    'Akka HTTP',
    'Apache Beam',
    'FastAPI',
    'Numpy',
    'Pandas',
    'Scikit Learn',
    'Spark',
    'XGBoost'
  ];
</script>

<h1 class="text-4xl font-semibold my-6">Resume</h1>

<div class="grid grid-cols-3 gap-5 text-sm">

  <div class="col-span-2">
    <!-- Education -->
    <h2 class="text-xl font-semibold mb-5">Education</h2>
    <div class="relative grid grid-cols-6 gap-y-5">
      <div class="h-full border-l border-slate-400 absolute left-[41.666667%] z-0"></div>

      <div class="col-span-2 flex flex-col items-end">
        <h3 class="text-right font-semibold">2015</h3>
        <div class="text-right text-slate-500">Ho Chi Minh City University of Technology</div>
      </div>

      <div class="z-10 w-3 h-3 mt-1 bg-white justify-self-center rounded-full border-2 border-sky-400 ring-4 ring-sky-200">
      </div>

      <div class="col-span-3">
       <p><span class="font-semibold">B.Eng</span> in <span class="font-semibold">Computer Science</span></p>
       <p>Honor Program</p>
       <p>GPA 8.45/10</p>
      </div>
    </div>

    <!-- Experience -->
    <h2 class="text-xl font-semibold mt-6 mb-5">Experience</h2>
    <div class="relative grid grid-cols-6 gap-y-5">
      <div class="h-full border-l border-slate-400 absolute left-[41.666667%] z-0"></div>

      <!-- PayMaya -->
      <div class="col-span-2 flex flex-col">
        <h3 class="text-right font-semibold">Jan. 2022 - Current</h3>
        <div class="text-right text-slate-500">Maya, Metro Manila</div>
      </div>
      <div class="z-10 w-3 h-3 mt-1 bg-white justify-self-center rounded-full border-2 border-sky-400 ring-4 ring-sky-200"/>
      <div class="col-span-3">
        <h3 class="font-semibold">Machine Learning Engineer</h3>
        <ul class="list-disc marker:text-slate-500">
          <li>Developed pipelines to extract ML features.</li>
          <li>Developed batch model prediction and monitoring pipelines.</li>
          <li>Features Engineering.</li>
        </ul>
      </div>

      <!-- Be Group -->
      <div class="col-span-2 flex flex-col">
        <h3 class="text-right font-semibold">Sep. 2019 - Aug. 2021</h3>
        <div class="text-right text-slate-500">Be Group, HCMC</div>
      </div>
      <div class="z-10 w-3 h-3 mt-1 bg-white justify-self-center rounded-full border-2 border-sky-400 ring-4 ring-sky-200"/>
      <div class="col-span-3">
        <h3 class="font-semibold">Machine Learning Engineer</h3>
        <ul class="list-disc marker:text-slate-500">
          <li>Data lineage system for BigQuery.</li>
          <li>Python SQL Parser to get accessed columns for BigQuery.</li>
          <li>Devloped Drop-off location recommendation system.</li>
          <li>Developed and deployed Personas predictions using XGBoost over Spark.</li>
          <li>Developed and deployed automatic customer segmentation using KMeans and GMM.</li>
        </ul>
      </div>

      <!-- Refinitiv -->
      <div class="col-span-2 flex flex-col">
        <h3 class="text-right font-semibold">Sep. 2018 - Aug. 2019</h3>
        <div class="text-right text-slate-500">Refinitiv, Singapore</div>
      </div>
      <div class="z-10 w-3 h-3 mt-1 bg-white justify-self-center rounded-full border-2 border-sky-400 ring-4 ring-sky-200"/>
      <div class="col-span-3">
        <h3 class="font-semibold">Big Data Engineer</h3>
        <ul class="list-disc marker:text-slate-500">
          <li>Scala platform developer.</li>
          <li>Developed microservices for NLP tasks using Tensorflow and Scala.</li>
        </ul>
      </div>

      <!-- Trusting Social -->
      <div class="col-span-2 flex flex-col">
        <h3 class="text-right font-semibold">Jun. 2018 - Aug. 2018</h3>
        <div class="text-right text-slate-500">Trusting Social, HCMC</div>
      </div>
      <div class="z-10 w-3 h-3 mt-1 bg-white justify-self-center rounded-full border-2 border-sky-400 ring-4 ring-sky-200"/>
      <div class="col-span-3">
        <h3 class="font-semibold">Research Engineer</h3>
      </div>

      <!-- Placeholder -->

    </div>

    <!-- Teaching Experiences -->
    <h2 class="text-xl font-semibold mt-6 mb-5">Teaching Experience</h2>
    <div class="relative grid grid-cols-6 gap-y-5">
      <div class="h-full border-l border-slate-400 absolute left-[41.666667%] z-0"></div>

      <!-- VEFA -->
      <div class="col-span-2 flex flex-col">
        <h3 class="text-right font-semibold">2019-2021</h3>
        <div class="text-right text-slate-500">VEF Academy, HCMC</div>
      </div>
      <div class="z-10 w-3 h-3 mt-1 bg-white justify-self-center rounded-full border-2 border-sky-400 ring-4 ring-sky-200"/>
      <div class="col-span-3">
        <h3 class="font-semibold">Teaching Assistant</h3>
        <ul class="list-disc marker:text-slate-500">
          <li>Machine Learning Course, Fall 2020.</li>
          <li>Machine Learning Course, Fall 2021.</li>
        </ul>
      </div>

      <!-- UTDallas -->
      <div class="col-span-2 flex flex-col">
        <h3 class="text-right font-semibold">Aug. 2017 - May. 2018</h3>
        <div class="text-right text-slate-500">University of Texas at Dallas</div>
      </div>
      <div class="z-10 w-3 h-3 mt-1 bg-white justify-self-center rounded-full border-2 border-sky-400 ring-4 ring-sky-200"/>
      <div class="col-span-3">
        <h3 class="font-semibold">Teaching Assistant</h3>
        <ul class="list-disc marker:text-slate-500">
          <li>Software Engineering, Spring 2018.</li>
          <li>C/C++ Programming in a UNIX Environment, Spring 2018.</li>
          <li>C/C++ Programming in a UNIX Environment, Fall 2017.</li>
        </ul>
      </div>

      <!-- Bach Khoa -->
      <div class="col-span-2 flex flex-col">
        <h3 class="text-right font-semibold">Aug. 2015 - Aug. 2017</h3>
        <div class="text-right text-slate-500">Ho Chi Minh City University of Technology</div>
      </div>
      <div class="z-10 w-3 h-3 mt-1 bg-white justify-self-center rounded-full border-2 border-sky-400 ring-4 ring-sky-200"/>
      <div class="col-span-3">
        <h3 class="font-semibold">Research Assistant</h3>
        <h3 class="font-semibold">Teaching Assistant</h3>
        <ul class="list-disc marker:text-slate-500">
          <li>Programming Fundamentals.</li>
          <li>Artificial Intelligence.</li>
          <li>Operating Systems.</li>
        </ul>
      </div>

    </div>

  </div>

  <!-- Right Section -->
  <div class="">
    <!-- Skills -->
    <h2 class="text-xl font-semibold mb-5">Skills</h2>
    {#each skills as s}
      <div class="flex justify-between mb-1">
        <span class="font-semibold">{s.name}</span>
        <span class="text-slate-500">{s.percent}%</span>
      </div>
      <div class="w-full bg-sky-200 rounded-full h-2 mb-3">
        <div class="bg-sky-400 h-2 rounded-full" style="width:{s.percent}%;"></div>
      </div>
    {/each}

    <!-- Knowledges -->
    <h2 class="text-xl font-semibold mt-6 mb-5">Knowledges</h2>
    <div class="flex flex-wrap gap-2 text-sm font-normal">
      {#each knowledges as k}
        <p class="bg-sky-400 rounded-md py-0.5 px-3 text-white">{k}</p>
      {/each}
    </div>
  </div>

  <!-- Pakge Break for printing -->
  <div class="print:h-20">
  </div>

  <div class="col-span-3">
    <!-- Papers -->
    <h2 class="text-xl font-semibold mt-6 mb-5">Papers</h2>
    <ul class="list-disc list-inside marker:text-sky-400">
      <li>Diep, Thanh-Dang & Nguyen, Minh-Tri & Nguyen-Huynh, Nhu-Y & Chung, Minh & Nguyen, Manh-Thin & Nguyen, Hung & Thoai, Nam. (2018). Chainer-XP: A Flexible Framework for ANNs Run on the Intel® Xeon PhiTM Coprocessor. <a href="http://dx.doi.org/10.1007/978-3-030-55240-4_7" target="_blank" class="text-sky-400">10.1007/978-3-030-55240-4_7</a>.</li>
      <li>M. T. Chung, M. Nguyen, N. Nguyen-Huynh, N. Thong and N. Thoai, "Performance evaluation of environmental applications using TELEMAC-MASCARET on virtual platforms," 2016 IEEE 12th International Conference on e-Science (e-Science), 2016, pp. 441-448, doi: <a href="https://doi.org/10.1109/eScience.2016.7870934" target="_blank" class="text-sky-400">10.1109/eScience.2016.7870934</a>.</li>
    </ul>

    <!-- Certificates -->
    <h2 class="text-xl font-semibold mt-6 mb-5">Certificates</h2>

    <div class="flex flex-row gap-2">
      <div class="basis-1/2 flex flex-row rounded-md ring-1 ring-slate-400 h-24 py-0">
        <img class="w-24"
          src="https://edxuploads.s3.amazonaws.com/organization_logos/6f244695-7416-4c6c-a2a9-97769b6acb56-bcd257616243.png" alt="EPFL"/>
        <div class="flex flex-col py-4 px-2">
          <a class="font-semibold" href="https://courses.edx.org/certificates/30f4c1f673df4e7e8e90766f6addcc92" target="_blank">
            Optimization: principles and algorithms - Linear optimization
          </a>
          <span>September 12, 2021</span>
        </div>
      </div>

    </div>

  </div>

</div>
