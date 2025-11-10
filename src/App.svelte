<script lang="ts">
  import Home from './lib/Home.svelte'
  import CurriculumLibrary from './lib/CurriculumLibrary.svelte'
  import About from './lib/About.svelte'
  import Contributors from './lib/Contributors.svelte'
  import MyAccount from './lib/MyAccount.svelte'
  import GoalOverview from './lib/GoalOverview.svelte'
  import SubjectPage from './lib/SubjectPage.svelte'
  import LessonPage from './lib/LessonPage.svelte'
  
  let currentPage = 'home'; // 'home', 'curriculum', 'about', 'contributors', 'myaccount', 'goaloverview', 'subject', or 'lesson'
  
  function navigateTo(page: string) {
    currentPage = page;
  }
</script>

<main>
  {#if currentPage === 'home'}
      <Home {currentPage} {navigateTo} />
    {:else if currentPage === 'curriculum'}
      <CurriculumLibrary {currentPage} {navigateTo} />
    {:else if currentPage === 'about'}
      <About {currentPage} {navigateTo} />
    {:else if currentPage === 'contributors'}
      <Contributors {currentPage} {navigateTo} />
    {:else if currentPage === 'myaccount'}
      <MyAccount {navigateTo} />
    {:else if currentPage === 'goaloverview'}
      <GoalOverview {navigateTo} />
    {:else if currentPage === 'subject'}
      <SubjectPage {navigateTo} />
    {:else if currentPage === 'lesson'}
      <LessonPage {navigateTo} />
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
