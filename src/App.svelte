<script lang="ts">
  import Testimonials from "./lib/Testimonials.svelte";
</script>

<main>
  <div class="card">
    <h1>Svelte Slider</h1>
    <Testimonials />
  </div>
</main>

<style>
  h1 {
    text-align: center;
  }
  
  @media (max-width: 768px) {
  h1 {
    font-size: 2em;
  }
}
</style>
