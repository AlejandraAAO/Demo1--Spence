<template>
  <section class="font-cabin w-screen">
    <section class="font-bold p-4 text-center sticky top-0 bg-black text-white">
      <p class="lg:inline">
        🎉 To celebrate Spense`s launch, we will be waiving al free for the
        entire month of April.
      </p>
      <p class="underline lg:inline">
        You will be receiving 100% of the earnings. 🎉
      </p>
    </section>
    <section class="bg-gray-200">
      <header
        class="flex flex-row justify-between px-8 lg:px-36 py-10 font-bold"
      >
        <p class="text-xl align-middle md:py-3">spense.</p>

        <div
          class="
            hidden
            md:flex
            text-lg
            md:py-3 md: md:flex-grow md:justify-end
            lg:flex-grow-0 lg:justify-self-center
          "
        >
          <button class="mx-3">Business</button>
          <button class="mx-3">Pricing</button>
          <button class="mx-3">Features</button>
        </div>
        <div class="hidden md:block text-lg lg:justify-self-end">
          <button class="mx-3">Login</button>
          <button class="ml-3 bg-black text-white px-5 py-3 rounded">
            Get Started
          </button>
        </div>
        <svg
          class="md:hidden"
          width="24"
          height="20"
          viewBox="0 0 24 20"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M24 4H0V0H24V4ZM24 8H0V12H24V8ZM24 16H0V20H24V16Z"
            fill="black"
          />
        </svg>
      </header>
      <main class="px-8 lg:hidden">
        <picture>
          <img
            class="md:hidden"
            src="../assets/hero-mobile.png"
            alt="Share your unfiltered thoughts"
          />
          <img
            class="hidden md:block"
            src="../assets/hero-tablet.png"
            alt="Share your unfiltered thoughts"
          />
        </picture>
      </main>
    </section>
    <section class="bg-gray-200 px-8 lg:px-36 lg:flex lg:flex-row pb-12">
      <div class="lg:w-3/5 lg:flex lg:flex-col lg:justify-center">
        <div>
          <h1 class="pt-10 pb-2 md:pb-4 font-bold text-4xl md:text-6xl">
            Share your unfiltered thoughts. Get paid.
          </h1>
          <p class="text-gray-700 text-lg">
            Spense is an open platform for individuals to share their unfiltered
            thoughts. Discuss the topics you love, and get paid for doing
            <span class="italic">just</span> that.
          </p>
        </div>
        <div class="text-gray-700 py-4 text-lg font-medium">
          <div class="flex flex-row py-0.5" v-for="(item, l) in list" :key="l">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M12 0C5.373 0 0 5.373 0 12C0 18.627 5.373 24 12 24C18.627 24 24 18.627 24 12C24 5.373 18.627 0 12 0ZM10.75 17.292L6.25 12.928L8.107 11.07L10.75 13.576L16.393 7.792L18.25 9.649L10.75 17.292Z"
                fill="black"
              />
            </svg>
            <p class="pl-4">{{ item }}</p>
          </div>
        </div>
        <div class="flex flex-row justify-between md:justify-start text-lg">
          <input
            class="w-3/5 md:w-auto border border-gray-400 rounded px-4"
            type="text"
            placeholder="john@example.com"
          />
          <button class="p-4 md:ml-4 rounded bg-black text-white font-bold">
            Get Started
          </button>
        </div>
      </div>

      <div class="hidden lg:block lg:w-2/5">
        <picture>
          <img
            src="../assets/hero-desktop.png"
            alt="Share your unfiltered thoughts"
          />
        </picture>
      </div>
    </section>
    <section class="bg-white px-8 lg:px-32">
      <div
        class="
          grid grid-cols-3
          md:grid-cols-5
          lg:grid-cols-8
          gap-7
          lg:gap-9
          w-full
          py-10
         
          justify-evenly
          items-center
        "
      >
        <img class="" src="../assets/facebook-logo.png" alt="" />
        <img class="" src="../assets/dribbble-logo.png" alt="" />
        <img class="" src="../assets/youtube-logo.png" alt="" />
        <img class="hidden md:block" src="../assets/pinterest-logo.png" alt="" />
        <img class="hidden md:block" src="../assets/twitter-logo.png" alt="" />
        <img class="hidden lg:block" src="../assets/reddit-logo.png" alt="" />
        <img class="hidden lg:block" src="../assets/google-logo.png" alt="" />
        <img class="hidden lg:block" src="../assets/slack-logo.png" alt="" />
      </div>
      <div class="bg-gray-200 rounded-xl lg:flex lg:flex-row">
        <div class="px-8 md:px-28 lg:pl-28 lg:pr-20 lg:w-3/5 lg:flex lg:flex-col lg:justify-center">
          <h1 class="pt-10 md:pt-14 lg:pt-1 pb-2 font-bold text-4xl md:pr-40">
            Secure your money with Escrow.
          </h1>
          <p class="text-gray-700 text-lg md:pr-14">
            Spense uses Escrow to secure all payments. We believe Escrow offers
            the highest level of security for your payments, so you never nedd
            to worry about scams.
          </p>
          <p class="pt-4 font-bold text-gray-700 text-lg underline">
            Learn more about Escrow →
          </p>
        </div>
        <div class="flex flex-row justify-center lg:block lg:w-2/5">
          <picture>
            <img
              class="md:hidden lg:block lg:w-full"
              src="../assets/phone-mobile.png"
              alt="Phone with text: Never buy or sell online witout using Escrow.com"
            />
            <img
            class="lg:hidden hidden"
              src="../assets/phone-tablet.png"
              alt="Phone with text: Never buy or sell online witout using Escrow.com"
            />
          </picture>
        </div>
      </div>
    </section>
    <section class="bg-white px-8 lg:px-32 lg:flex lg:flex-row-reverse">
      <div class="lg:w-1/2 lg:flex lg:flex-col lg:justify-center">
        <h1 class="pt-10 pb-2 font-bold text-4xl">
          A text editor like no other.
        </h1>
        <p class="text-gray-700 text-lg">
          Our text editor pulls you into focus mode with it's simplistic design
          and usability so you can put out your best writings.
        </p>
        <p class="pt-4 font-bold text-gray-700 text-lg underline">
          Text Editor Live Demo →
        </p>
      </div>
      <div  class="lg:w-1/2 lg:pt-16">
        <picture>
          <img src="../assets/text-editor.png" alt="Text editor" />
        </picture>
      </div>
    </section>
    <footer class="bg-black px-8 py-14 lg:px-32">
      <div class="pt-4 grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 md:gap-6 text-xl">
        <div class="col-span-2">
          <h1 class="font-bold text-xl text-white py-4">spense.</h1>
          <p class="text-gray-400 text-lg">
            Spence is an open platform for individuals to share their unfilteres
            thoughts. Discuss the topics you love, and get paid for doing
            <span class="italic">just</span> that.
          </p>
        </div>
        <div class="order-4">
          <h3 class="text-white font-bold py-4">Company</h3>
          <ul class="text-gray-400">
            <li class="pb-2">About</li>
            <li class="pb-2">Customers</li>
            <li class="pb-2">Blog</li>
          </ul>
        </div>
        <div class="order-5">
          <h3 class="text-white font-bold py-4">Opportunities</h3>
          <ul class="text-gray-400">
            <li>Jobs</li>
          </ul>
        </div>
        <div class="order-2">
          <h3 class="text-white font-bold py-4">Sitemap</h3>
          <ul class="text-gray-400">
            <li>Homepage</li>
          </ul>
        </div>
        <div class="order-3">
          <h3 class="text-white font-bold py-4">Resources</h3>
          <ul class="text-gray-400">
            <li class="pb-2">Support</li>
            <li class="pb-2">Contact</li>
            <li class="pb-2">FAQ</li>
          </ul>
        </div>
      </div>
    </footer>
  </section>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home",
  components: {},
  data() {
    return {
      list: [
        "Receive 99% off the aernings.",
        "Get paid via Debit Card, ACH, or PayPal.",
        "Withdraw your earnings anytime.",
      ],
    };
  },
});
</script>
