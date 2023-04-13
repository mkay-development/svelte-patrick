<script>
  import { faSmile } from "@fortawesome/free-solid-svg-icons";
  import Fa from "svelte-fa";
</script>

<div class="grid grid-cols-6 gap-3">
  <div class="col-span-6 md:col-span-3 my-6 md:my-12">
    <h2 class="font-bold text-lg text-center">
      Willkommen bei Patrick's Felgen Service
    </h2>
    <p class="text-center">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellendus
      consequuntur praesentium ad harum quas tempora, odio ea pariatur fugiat in
      magni aut porro tenetur obcaecati asperiores necessitatibus voluptatibus
      vitae labore!
    </p>
    <div class="grid grid-cols-6 gap-3">
      <div class="col-span-6 md:col-span-2">
        <Fa icon={faSmile} class="mx-auto mt-6" size="3x" />
        <h2 class="font-bold text-center mt-3">Reparatur</h2>
        <p class="text-sm text-center">Lorem ipsum dolor sit.</p>
      </div>
      <div class="col-span-6 md:col-span-2">
        <Fa icon={faSmile} class="mx-auto mt-6" size="3x" />
        <h2 class="font-bold text-center mt-3">Reparatur</h2>
        <p class="text-sm text-center">Lorem ipsum dolor sit.</p>
      </div>
      <div class="col-span-6 md:col-span-2">
        <Fa icon={faSmile} class="mx-auto mt-6" size="3x" />
        <h2 class="font-bold text-center mt-3">Reparatur</h2>
        <p class="text-sm text-center">Lorem ipsum dolor sit.</p>
      </div>
    </div>
  </div>
  <div class="col-span-6 md:col-span-3">
    <img
      src="https://avatars.githubusercontent.com/u/20771653?v=4"
      class="w-24 rounded-full mx-auto mt-12"
      alt=""
    />
    <h2 class="font-bold text-center mt-3">Patrick Doe</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores, beatae
      doloremque a ab ipsam temporibus cupiditate? Vitae enim hic iste, earum
      nisi error quod repellat mollitia labore doloremque. Amet, nobis.
    </p>
  </div>
  <div class="col-span-6 md:col-span-2">Test</div>
  <div class="col-span-6 md:col-span-2">Test</div>
  <div class="col-span-6 md:col-span-2">Test</div>
</div>
