<template>
    <div class="banner-1">
      <!-- NavBar -->
      <nav
        class="container px-6 mx-auto md:flex md:justify-between md:items-center"
      >
        <div class="flex items-center justify-between">
          <div class="relative w-28">
            <img
              src="/src/assets/Logo PORTFOLIO.svg"
              alt="user image"/>
          </div>
          <!-- Mobile menu button -->
          <div @click="showMenu = !showMenu" class="flex md:hidden">
            <button
              type="button"
              class="text-gray-800 hover:text-gray-400 focus:outline-none focus:text-gray-400"
            >
              <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
                <path
                  fill-rule="evenodd"
                  d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
                ></path>
              </svg>
            </button>
          </div>
        </div>
        <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
        <ul
          :class="showMenu ? 'flex' : 'hidden'"
          class="flex-col items-end mt-8 space-y-4 md:flex md:space-y-0 md:flex-row md:items-center md:space-x-10 md:mt-0" 
        >
          <li class="menu-button"><a href="#PROJECTS">PROJECTS</a></li>
          <li class="menu-button"><a href="#ABOUTME">ABOUT ME</a></li>
          <li class="menu-button"><a href="#CONTACT">CONTACT</a></li>
        </ul>
      </nav>
      <!-- End Navbar -->
  
      <div class="flex items-center">
        <div class="w-11/12 space-y-5 md:space-y-10">
          <h3
            class="hello-button w-fit md:py-3 md:px-5 py-1 px-2 3xl:text-3xl 2xl:text-xl lg:text-xl md:text-md text-sm font-amandine" style="color: #384b47;">
            <span style="color: #d3e8d6;">✌🏼 HELLO</span>
          </h3> 
          <h1
            class="3xl:text-8xl 2xl:text-7xl xl:text-6xl lg:text-4xl md:text-3xl sm:text-3xl text-xl font-bold leading-tight" style="color: #384b47;"
          >
            It's
            <a
              href="https://www.linkedin.com/in/marin-vujica/"
              target="_blank"
              class="hover:underline"
            >
              MARIN VUJICA</a> Freelance Graphic Designer</h1>
  
          <div class="md:flex gap-1 md:gap-10">
            <button class="submit-button hidden md:block" style="color: #384b47;">
                <a href="https://youtu.be/DnjCWJMrWko">
                WATCH MY VIDEO CV </a>
            </button>
            <button
              class="submit-button mb-5 md:mb-0" style="color: #384b47;">
              <a href="https://acrobat.adobe.com/id/urn:aaid:sc:EU:ab6f3c3d-ad90-4aa8-8169-452c0a258115">
              READ MY CV </a>
            </button>
          </div>
        </div>
  
        <div class="w-8/12 flex justify-end">
          <img
            class="3xl:h-[800px] 2xl:h-[650px] xl:h-[550px] lg:h-[550px] md:h-[450px] sm:h-[350px]"
            src="./assets/Profile picture Marin.jpg"
            alt="user image"
          />
        </div>
      </div>
    </div>
  
    <div class="banner-2 space-y-10 pb-20" id="PROJECTS">
      <h3 class="heading3 my-5">MY RECENT PROJECTS</h3>
      
      

      <div class="card">
        <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-1/2">
          <h4 class="project-title item">TRAPHOLT MUSEUM</h4>
          <p class="pr-12">
            Our team of 4 took on a project to develop a comprehensive visual identity and website for Trapholt Museum in Kolding, with a specific focus on targeting a particular group of people. We began by doing research to understand the preferences and interests of our target audience. Using this information as a guide, we collaborated closely to create a cohesive visual identity with elements such as a logo, color palette, typography, and overall design style made to resonate with our chosen demographic.
          </p>
          <button
              class="submit-button mb-5 md:mb-0" style="color: #d3e8d6;">
              <a href="https://acrobat.adobe.com/id/urn:aaid:sc:EU:61fb6da3-db73-4355-871e-4dcb9588cde4">
              READ THE REPORT </a>
            </button>
        </div>
        <div class="card-image">
          <img
            class="object-cover w-full h-48 md:h-96"
            src="./assets/poster 2.jpg"
          />
        </div>
      </div>

      <div
  class="block   shadow-secondary-1 dark:bg-surface-dark dark:text-white text-surface">
  <div class="relative overflow-hidden bg-cover bg-no-repeat">
    <img
      class="rounded-t-lg"
      src="/src/assets/trapholt.jpg"
      alt="" />
  </div>
  <div class="p-6">
    
    <button
              class="submit-button mb-5 md:mb-0" style="color: #384b47;">
              <a href="https://jakubrepa.github.io/index.html">
              LOOK THE WEBSITE </a>
            </button>
  </div>
</div>

  
      <div class="card">
        <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-1/2">
          <h4 class="project-title item">PHOTOGRAPHY</h4>
          <p class="pr-12">
            I really enjoy taking pictures outdoors as a hobby. It's something I love doing, and it has actually helped me get interested in graphic design as a job. When I take photos outside, I started playing around with editing them on my computer. This got me thinking more about how things look and fit together in a picture. Eventually, I realized I wanted to explore graphic design more because it lets me be creative in a similar way to taking photos. It's been a smooth transition from just enjoying photography to wanting to do design as a career.
          </p>
           <br> <h class="font-bold text-2xl tracking-wider" style="color: #d3e8d6;">
            VIEW MORE PHOTOS DOWN 👇🏼
          </h>
        </div>
        <div class="card-image">
          <img
            class="object-cover w-full h-48 md:h-96"
            src="./assets/20210228_141049.jpg"
          />
        </div>
      </div>

      <div class="grid-cols-1 sm:grid md:grid-cols-2">
  <div
    class="mx-3 mt-6 flex flex-col self-start   text-surface shadow-secondary-1 dark:bg-surface-dark dark:text-white sm:shrink-0 sm:grow sm:basis-0">
    <a href="#!">
      <img src="./assets/1641917925630.jpg"
        />
    </a>
    <div class="p-6">
      <h5 class="mb-2 text-xl font-bold leading-tight" style="color: #384b47;">Nature</h5>
      
    </div>
  </div>

  <div
    class="mx-3 mt-6 flex flex-col self-start text-surface shadow-secondary-1 dark:bg-surface-dark dark:text-white sm:shrink-0 sm:grow sm:basis-0">
    <a href="#!">
      <img src="/src/assets/1609694638576.jpg"
        alt="Palm Springs Road" />
    </a>
    <div class="p-6">
      <h5 class="mb-2 text-xl font-bold leading-tight" style="color: #384b47;">Mountains</h5>
      
    </div>
  </div>

  <div
    class="mx-3 mt-6 flex flex-col self-start  text-surface shadow-secondary-1 dark:bg-surface-dark dark:text-white sm:shrink-0 sm:grow sm:basis-0">
    <a href="#!">
      <img src="/src/assets/20230905_200110.jpg"
        alt="Skyscrapers" />
    </a>
    <div class="p-6">
      <h5 class="mb-2 text-xl font-bold leading-tight" style="color: #384b47;">More Life</h5>
      
    </div>
  </div>

  <div
    class="mx-3 mt-6 flex flex-col self-start  text-surface shadow-secondary-1 dark:bg-surface-dark dark:text-white sm:shrink-0 sm:grow sm:basis-0">
    <a href="#!">
      <img src="/src/assets/1693136953010.jpg"
        alt="Los Angeles Skyscrapers" />
    </a>
    <div class="p-6">
      <h5 class="mb-2 text-xl font-bold leading-tight" style="color: #384b47;">Heart Lake</h5>
      
    </div>
  </div>
</div>

      <div class="card">
        <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-1/2">
          <h4 class="project-title item">FLYER</h4>
          <p class="pr-12">
            Me and another student worked together on a project using Adobe InDesign to make a flyer about one part of the Esbjerg. We made a cool flyer for the area called Saedding in our city. First, we came up with ideas and thought about who would see the flyer. Then, we used InDesign to create it, trying out different tools until it looked just right. We got feedback from each other and made changes until the flyer looked proffesional and good. We also had to use our own photos and think how to organize it with proper content. It was a fun way to learn about InDesign and make something cool for our city! </p>
            <button
              class="submit-button mb-5 md:mb-0" style="color: #d3e8d6;">
              <a href="https://indd.adobe.com/view/2f04ccab-ca61-415d-87d2-07a453718cff">
              READ THE FLYER </a>
            </button>
        </div>
        <div class="card-image">
          <img
            class="object-cover w-full h-72 md:h-96"
            src="./assets/FLYER.jpg"
          />
        </div>
      </div>

      

  <div
  class="flex flex-col rounded-lg bg-white text-surface shadow-secondary-1 dark:bg-surface-dark dark:text-white md:max-w-xl md:flex-row">
  <img
    class="h-96 w-full  object-cover md:h-auto md:w-48 md:!rounded-none "
    src="./assets/_MiniMi.jpg"
    alt="" />
  <div class="flex flex-col justify-start p-6">
    <h5 class="mb-2 text-xl font-bold" style="color: #384b47;">ILLUSTRATION</h5>
    <p class="mb-4 text-base" style="color: #384b47;">
      As part of a study assignment to practice using Adobe Illustrator, I had a fun project to create a creative, imaginary illustration of myself. I started by learning the basics of Illustrator, like how to draw shapes, use colors, and add details. It was exciting to see how I could bring my ideas to life on the computer screen, and the process helped me improve my skills in digital art and illustration. This project not only allowed me to express my creativity but also gave me valuable experience using Illustrator for future design projects.</p>
    
  </div>
</div>
  
      <div class="card">
        <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-1/2">
          <h4 class="project-title">REMOTE HUNT APP</h4>
          <p class="pr-12">
            Our team of 4 worked together to create a student remote jobs app. We started by talking to students to learn what they needed. Then we came up with ideas for the app and tested them to see what worked best. We listened to feedback from students to make sure the app was easy to use. Now, students can easily find remote job opportunities with our app!
          </p>
          <button
              class="submit-button mb-5 md:mb-0" style="color: #d3e8d6;">
              <a href="https://www.figma.com/proto/MmvKeKjJvgY9pLrzl4t5pm/app?page-id=0%3A1&node-id=101-1744&scaling=scale-down&starting-point-node-id=101%3A2979&mode=design&t=fUK30KbBTjHePWd0-1">
              VIEW APP PROTOTYPE </a>
            </button>
        </div>
        <div class="card-image">
          <img
            class="object-cover w-full h-72 md:h-96"
            src="./assets/app .jpg"
          />
        </div>
      </div>
    </div>
  
    <div class="banner-2 md:flex items-center md:justify-evenly" id="ABOUTME">
      <img
        class="md:h-[500px] h-[400px]"
        src="/src/assets/Profile picture Marin.jpg"
        alt="user image"
      />
      <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-1/2">
        <h4 class="project-title item" style="color: #384b47;">ABOUT ME </h4>
        <p class="font-amandine" style="color: #384b47;">
            I am Marin Vujica, I am 25 year old Croatian. At the moment I study Multimedia Design at Erhvervsakademi SydVest in Esbjerg.
          <br />
          I have a lot of work experiences in various areas in different countries. With my curious personality, I’m open to try myself in new environments and do something new and grow along the way. I’m a quick learner and I can addapt to any environment because of my ability to have a good comunnication with people and my social personality. Along the way I have learned to be responsible and do my best for any company I worked at that moment. To push myself outside of my comfort zone & grow as a human being while doing my best. I look forward for a new job opportunity in Graphic Design area as a young student here in Esbjerg, best regards!
        </p>
        
      </div>
    </div>
  
    <div class="banner-1 flex h-full items-center" id="CONTACT">
      <div class="w-7/12 p-12" style="color: #384b47;">
        <h2 class="md:text-6xl text-2xl mb-5 font-bold">Let’s work together and make good looking and useful design for your future projects.</h2>
        
        <a class="text-2xl" style="color: #384b47;" href="mailto:vujojr@gmail.com">vujojr@gmail.com</a>

      </div>
      <div class="w-5/12 pr-28">
        <div class="flex flex-wrap justify-end gap-2">
        <button
            class="bg-gray-700 p-2 font-semibold text-white inline-flex items-center space-x-2 rounded"
          >
            <svg
              class="w-4 h-4 md:w-10 md:h-10 lg:w-10 lg:h-10 xl:h-10 xl:w-10 fill-current"
              role="img"
              viewBox="0 0 256 256"
              xmlns="http://www.w3.org/2000/svg"
            >
              <g>
                <path
                  d="M218.123122,218.127392 L180.191928,218.127392 L180.191928,158.724263 C180.191928,144.559023 179.939053,126.323993 160.463756,126.323993 C140.707926,126.323993 137.685284,141.757585 137.685284,157.692986 L137.685284,218.123441 L99.7540894,218.123441 L99.7540894,95.9665207 L136.168036,95.9665207 L136.168036,112.660562 L136.677736,112.660562 C144.102746,99.9650027 157.908637,92.3824528 172.605689,92.9280076 C211.050535,92.9280076 218.138927,118.216023 218.138927,151.114151 L218.123122,218.127392 Z M56.9550587,79.2685282 C44.7981969,79.2707099 34.9413443,69.4171797 34.9391618,57.260052 C34.93698,45.1029244 44.7902948,35.2458562 56.9471566,35.2436736 C69.1040185,35.2414916 78.9608713,45.0950217 78.963054,57.2521493 C78.9641017,63.090208 76.6459976,68.6895714 72.5186979,72.8184433 C68.3913982,76.9473153 62.7929898,79.26748 56.9550587,79.2685282 M75.9206558,218.127392 L37.94995,218.127392 L37.94995,95.9665207 L75.9206558,95.9665207 L75.9206558,218.127392 Z M237.033403,0.0182577091 L18.8895249,0.0182577091 C8.57959469,-0.0980923971 0.124827038,8.16056231 -0.001,18.4706066 L-0.001,237.524091 C0.120519052,247.839103 8.57460631,256.105934 18.8895249,255.9977 L237.033403,255.9977 C247.368728,256.125818 255.855922,247.859464 255.999,237.524091 L255.999,18.4548016 C255.851624,8.12438979 247.363742,-0.133792868 237.033403,0.000790807055"
                ></path>
              </g>
            </svg>
        </button>
        </div>
      </div>
    </div>
  </template>
  <script>
   

    
  </script>
  