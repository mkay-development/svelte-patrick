<script>
  import "../tailwind.css";
  import Fa from "svelte-fa";
  import { faHeart } from "@fortawesome/free-solid-svg-icons";
</script>

<svelte:head>
  <script
    defer
    data-domain="patrick.mkay.dev"
    src="https://bhkenqpeta4iu6t.plausible.dev/js/script.js"
  ></script>
</svelte:head>

<header class="mx-auto max-w-5xl my-2 flex justify-between px-2 py-2">
  <h1 class="text-xl font-bold"><a href="/">Patrick's Felgen</a></h1>
  <nav class="desktop md:block hidden">
    <ul class="flex space-x-10">
      <li class="list-disc">Test</li>
      <li class="list-disc">Test</li>
      <li class="list-disc">Test</li>
      <li class="list-disc">Test</li>
    </ul>
  </nav>
</header>

<main class="mx-auto max-w-5xl my-2 px-2 py-2"><slot /></main>

<footer class="mx-auto max-w-5xl my-2 px-2 py-2">
  <div class="grid grid-cols-6">
    <div class="col-span-6 md:col-span-2">
      <a href="/impressum">Impressum</a> &
      <a href="/data-privacy">Datenschutz</a>
    </div>
    <div class="col-span-6 md:col-span-2 flex">
      Made with <Fa icon={faHeart} class="mx-2 mt-1 text-red-400" /> by Jonathan
    </div>
    <div class="col-span-6 md:col-span-2">
      Copyright by <a
        href="https://www.mkay-development.de"
        class="text-blue-600">MkaY Development</a
      >
    </div>
  </div>
</footer>
