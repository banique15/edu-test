<script lang="ts">
  import Home from './lib/Home.svelte'
  import CurriculumLibrary from './lib/CurriculumLibrary.svelte'
  
  let currentPage = 'home'; // 'home' or 'curriculum'
  
  function navigateTo(page: string) {
    currentPage = page;
  }
</script>

<main>
  {#if currentPage === 'home'}
    <Home {currentPage} {navigateTo} />
  {:else if currentPage === 'curriculum'}
    <CurriculumLibrary {currentPage} {navigateTo} />
  {/if}
</main>

<style>
  main {
    width: 100%;
    min-height: 100vh;
    margin: 0;
    padding: 0;
  }

  :global(body) {
    margin: 0;
    padding: 0;
  }
</style>
