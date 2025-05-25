<script setup>

</script>

<template>


  <head>
    <title>Smart Health Monitoring Wristwatch</title>
    <link rel="stylesheet" href="https://unpkg.com/tailwindcss/dist/tailwind.min.css" />
    <link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,400i,700" rel="stylesheet" />
  </head>

  <body class="" style="font-family: 'Source Sans Pro', sans-serif">

    <!--Nav-->

    <nav class="">
      <div class="flex flex-row justify-between py-5 px-10">
        <a class="font-bold text-3xl" href="#"> SHMW </a>
        <div class="">
          <button class="">
            <svg class="" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <title>Menu</title>
              <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
            </svg>
          </button>
        </div>
        <div class="">
          <ul class="flex flex-row space-x-5">
            <li>
              <a class="" href="/">Home</a>
            </li>
            <li>
              <a class="" href="#">About</a>
            </li>
            <li>
              <a class="" href="#">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!--Hero-->

    <div class="py-16 px-10" style="background: linear-gradient(90deg, #667eea 0%, #764ba2 100%)">
      <div class="space-y-5">
        <h2 class="text-white font-bold text-3xl">Smart Health Monitoring Wristwatch!</h2>
        <h3 class="text-white text-xl">Monitor your health vitals smartly anywhere you go.</h3>
        <button class="bg-white font-bold text-sm py-3 px-6 rounded-full uppercase">Pre Order</button>
      </div>
    </div>

    <!-- Features -->

    <section class="grid grid-cols-1 px-10">

      <h2 class="font-bold text-3xl text-center mb-5">Features</h2>

      <div class="flex flex-row">
        <div class="space-y-4">
          <h4 class="font-bold text-2xl">Exercise Metrics</h4>
          <p class="">Our Smart Health Monitoring Wristwatch is able to capture you vitals while you exercise. You can
            create different category of exercises and can track your vitals on the go.</p>
        </div>

        <div class="">
          <img src="https://raw.githubusercontent.com/ammezie/tailwind_landing_page/master/assets/health.svg"
            alt="Monitoring" />
        </div>
      </div>

      <div class="flex flex-row">
        <div class="">
          <img src="https://raw.githubusercontent.com/ammezie/tailwind_landing_page/master/assets/report.svg"
            alt="Reporting" />
        </div>

        <div class="space-y-4">
          <h4 class="font-bold text-2xl">Reporting</h4>
          <p class="">Our Smart Health Monitoring Wristwatch can generate a comprehensive report on your vitals
            depending on your settings either daily, weekly, monthly, quarterly or yearly.</p>
        </div>
      </div>

      <div class="flex flex-row">
        <div class="space-y-4">
          <h4 class="font-bold text-2xl">Syncing</h4>
          <p class="">Our Smart Health Monitoring Wristwatch allows you to sync data across all your mobile devices
            whether iOS, Android or Windows OS and also to your laptop whether MacOS, GNU/LInux or Windows OS.</p>
        </div>
        <div class="">
          <img src="https://raw.githubusercontent.com/ammezie/tailwind_landing_page/master/assets/sync.svg"
            alt="Syncing" />
        </div>
      </div>
    </section>

    <!-- Testimonials -->

    <section class="bg-gray-200 py-16">
      <div class="">
        <h2 class="font-bold text-3xl text-center mb-10">Testimonials</h2>
        <div class="flex flex-row px-4 space-x-5">

          <div class="bg-white shadow-lg px-5">
            <div class="space-y-5">
              <p class="">Monitoring and tracking my health vitals anywhere I go and on any platform I use has never
                been easier.</p>
              <p class="text-gray-500">John Doe</p>
            </div>
          </div>

          <div class="bg-white shadow-lg px-5">
            <div class="space-y-5">
              <p class="">As an Athlete, this is the perfect product for me. I wear my Smart Health Monitoring
                Wristwatch everywhere i go, even in the bathroom since it's waterproof.</p>
              <p class="text-gray-500">Jane Doe</p>
            </div>
          </div>

          <div class="bg-white shadow-lg px-5">
            <div class="space-y-5">
              <p class="">I don't regret buying this wearble gadget. One of the best gadgets I own!.</p>
              <p class="text-gray-500">James Doe</p>
            </div>
          </div>

        </div>
      </div>
    </section>

    <!--Call to Action-->

    <section style="">
      <div class="bg-blue-500 flex flex-col items-center space-y-5 py-7">
        <h2 class="font-bold text-3xl text-white">Limited in Stock</h2>
        <h3 class="text-white text-xl">Get yourself the Smart Health Monitoring Wristwatch!</h3>
        <button class="bg-white font-bold text-sm py-3 px-6 rounded-full uppercase">Pre Order</button>
      </div>
    </section>

    <!--Footer-->
    <footer class="">
      <div class="">
        <div class="flex flex-row space-x-96 px-10 py-10">

          <div class="flex flex-col space-y-5">
            <h5 class="font-bold">Links</h5>
            <ul class="">
              <li class="">
                <a href="#" class="">FAQ</a>
              </li>
              <li class="">
                <a href="#" class="">Help</a>
              </li>
              <li class="mt-2">
                <a href="#" class="">Support</a>
              </li>
            </ul>
          </div>

          <div class="flex flex-col space-y-5">
            <h5 class="font-bold">Legal</h5>
            <ul class="">
              <li class="">
                <a href="#" class="">Terms</a>
              </li>
              <li class="mt-2">
                <a href="#" class="">Privacy</a>
              </li>
            </ul>
          </div>

          <div class="flex flex-col space-y-5">
            <h5 class="font-bold">Social</h5>
            <ul class="">
              <li class="">
                <a href="#" class="">Facebook</a>
              </li>
              <li class="mt-2">
                <a href="#" class="">Linkedin</a>
              </li>
              <li class="mt-2">
                <a href="#" class="">Twitter</a>
              </li>
            </ul>
          </div>

          <div class="flex flex-col space-y-5">
            <h5 class="font-bold">Company</h5>
            <ul class="">
              <li class="">
                <a href="#" class="">Official Blog</a>
              </li>
              <li class="mt-2">
                <a href="#" class="">About Us</a>
              </li>
              <li class="mt-2">
                <a href="#" class="">Contact</a>
              </li>
            </ul>
          </div>

        </div>
      </div>
    </footer>




  </body>


</template>
