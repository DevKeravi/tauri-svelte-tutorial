<script>
  import { base } from "$app/paths";
  import { component_subscribe } from "svelte/internal";

  // import "../app.css";
  import "../reset.css"
</script>

<main class="container">
  <slot />
  <style global lang="postcss">
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
  </style>
</main>
