<script lang="ts">
  import Menu from "./lib/components/Menu.svelte";
  import Toast from "./lib/components/Toast.svelte";

</script>

<Toast></Toast>

<main>
  <Menu></Menu>
</main>

<style>
  main {
    max-width: 32rem;
    margin-inline: auto;
  }
</style>