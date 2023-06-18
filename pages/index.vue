<template>
  <div>
    <navbar />
    <div class="mt-28 mx-48 hello">
      <div class="grid grid-cols-2">
        <div class="my-auto px-10	">
          <strong class="bold-text h2">👋</strong>
          <p class="text-5xl mb-7 font-bold">Hello , I am Rajveer Choudhary</p>
          <p class="font-semibold">I am a Product Designer with 10+ years experience, focusing in User Interface and User
            Experience. I am also
            a proud dog dad, and a board game enthusiast.</p>
        </div>
        <div class="object-cover ml-20">
          <img class="rounded-lg  w-96" src="/rajveer_photo.jpeg" title="Rajveer photo">
        </div>
      </div>
      <!-- Selected Work -->
      <div class="flex mt-24 pb-4 border-b-2 border-black">
        <div class="flex justify-start font-bold text-xl  place-content-center">
          <p class="h1">✍️</p>
          <p class="h2">Selected Work </p>

        </div>
        <div class="flex justify-end place-content-center ml-auto">
          <a href="https://www.linkedin.com/in/rajveer-choudhary-0b2931229" target="_blank "
            class="mr-2 font-semibold">View Dribbble</a>
          <p class="section-header-link icon my-auto mx-auto "><svg xmlns="http://www.w3.org/2000/svg" fill="none"
              viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-4 h-4">
              <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3" />
            </svg>
          </p>
        </div>
      </div>
      <!-- about -->
      <div class="flex mt-24 pb-4 border-b-2 border-black">
        <div class="flex justify-start font-bold text-xl  place-content-center">
          <p class="h1">👨‍💻</p>
          <p class="h2">About</p>
        </div>
        <div class="flex justify-end place-content-center ml-auto">
          <a href="https://www.linkedin.com/in/rajveer-choudhary-0b2931229" target="_blank "
            class="mr-2 font-semibold">View Linkedin</a>
          <p class="section-header-link icon my-auto mx-auto "><svg xmlns="http://www.w3.org/2000/svg" fill="none"
              viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-4 h-4">
              <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3" />
            </svg>
          </p>
        </div>
      </div>
      <div>
        <div class="grid grid-cols-2 mt-11">
          <div class="mx-5">
            <h4 class="heading-6">My Story</h4>
            <p class="body-paragraph">
              I have been a creative leader in the digital entertainment and software industry since 2011. During this
              time, I have had the opportunity to work with some amazing people on several cutting-edge projects. Projects
              I’ve worked on include an aviation simulation game (NFA) to conceptual products for multi-million dollar
              corporations (Amazon, KBB, and more).<br />
              <br />
              Along this journey, I have worn several hats ranging, including quality assurance, UI designer, product
              designer, creative director, product manager, producer, and Director of Product.<br />
              <br />As a designer, I have managed several small creative teams in creating innovative products and
              prototypes. As a creative leader and mentor, I strive to have my teams flourish by challenging them to be
              innovative and get out of their comfort zones.
            </p>
          </div>
          <div class="ml-4">
            <h4 class="heading-6">Where I &#x27;ve Worked</h4>
            <div class="div-block-6">
              <div class=" mb-25">
                <h5 class="h5">2021 - present</h5>
                <h5 class="body-paragraph high-emphasis">Grindr</h5>
                <h5 id="Company-Location" class="body-paragraph low-emphasis">Seattle, WA (Remote)</h5>
                <h5 class="body-paragraph">Senior Product Designer</h5>
              </div>
              <div class=" mb-25">
                <h5 class="h5">2020-2021</h5>
                <h5 class="body-paragraph high-emphasis">CommentSold</h5>
                <h5 id="Company-Location" class="body-paragraph low-emphasis">Seattle, WA (Remote)</h5>
                <h5 class="body-paragraph">Lead Product Designer</h5>
              </div>
              <div class=" mb-25">
                <h5 class="h5">2018–2020</h5>
                <h5 class="body-paragraph high-emphasis">Backbone PLM</h5>
                <h5 id="Company-Location" class="body-paragraph low-emphasis">Boulder, Colorado</h5>
                <h5 class="body-paragraph">Director of Product Design &amp;Senior Product Designer</h5>
              </div>
              <div class=" mb-25">
                <h5 class="h5">2015–2018</h5>
                <h5 class="body-paragraph high-emphasis">SNT Media, Inc.</h5>
                <h5 id="Company-Location" class="body-paragraph low-emphasis">San Francisco, California &amp;Wichita,
                  Kansas</h5>
                <h5 class="body-paragraph">Director of Product Design &amp;Senior Product Designer</h5>
              </div>
              <div class=" mb-25">
                <h5 class="h5">2012–2015</h5>
                <h5 class="body-paragraph high-emphasis">SNT Media, Inc.</h5>
                <h5 id="Company-Location" class="body-paragraph low-emphasis">San Francisco, CA</h5>
                <h5 class="body-paragraph">Product Designer</h5>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- contect us -->
      <div class="flex mt-24 pb-4 border-b-2 border-black">
        <div class="flex justify-start font-bold text-xl  place-content-center">
          <p class="h1">🤙</p>
          <p class="h2">Contact Us</p>
        </div>
      </div>
      <div class="mt-10  grid grid-cols-2 border-1 border-black">
        <div class=" grid grid-rows-2">
          <div>
            <p class="ml-2 font-semibold mb-6">
              Are you interested in collaborating or want to connect or chat? If so, hit the contact button down below or
              <a class="border-b-2 border-gray-500" href="https://www.linkedin.com/in/rajveer-choudhary-0b2931229"
                target="_blank">contact me via Linkedin</a>.
            </p>
          </div>
          <div>
            <!-- <a  class="rounded-none" href="mailto:rajveerjdh2021@gmail.com?subject=Contact%20via%20Portfolio" data-ix="new-interaction">Contact Me</a> -->
            <button class="rounded my-2 mx-2 px-4 py-3 w-44 h-14 bg-gray-500"
              href="mailto:rajveerjdh2021@gmail.com?subject=Contact%20via%20Portfolio" data-ix="new-interaction">Contact
              Me</button>
          </div>
        </div>
        <div>
          <img src="#" alt="" class="image-placement small" />
          <img src="#" alt="" class="image-placement small long" />
        </div>
      </div>
    </div>

    <!-- <div class="mt=96 pt-96">hello dd</div> -->
  </div>
</div></template>


<script lang="ts">
import Vue from 'vue'
import Navbar from '../components/navbar.vue'

export default Vue.extend({
  name: 'IndexPage',
})
Navbar
</script>

<style >
template {
  font-family: 'Helvetica Now', sans-serif;
}

.section-header-link {
  font-family: 'Fa 300', sans-serif;
}

/* .hello {
  border: 1px solid black;
} */
</style>

