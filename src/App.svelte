<script>
  import Counter from './lib/Counter.svelte'
  import Header from './lib/Header.svelte';
</script>
<main>
  <Header status="main" />  
  
<section class="hero"></section>

  <div class="card">
    <Counter />
  </div>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme" rel="noreferrer" target="_blank">SvelteKit</a>, the official Svelte app framework powered by Vite!
  </p>

  <p class="read-the-docs">
    Click on the Vite and Svelte logos to learn more
  </p>
</main>
<style>
  .read-the-docs {
    color: #888;
  }
  .hero {
    width: 100%;
    height: 70vh;
    background-image: url('./assets/herobg.jpg');
    background-size: cover;
  }
</style>
