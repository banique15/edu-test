<script lang="ts">
  export let currentPage = '';
  export let isLoggedIn = false;
  export let backgroundColor = 'green'; // 'green' or 'white'
  export let navigateTo: (page: string) => void = () => {};

  function handleNavigation(page: string, event: Event) {
    event.preventDefault();
    navigateTo(page);
  }

  function handleLogoClick() {
    navigateTo('home');
  }

  function handleLogoKeydown(event: KeyboardEvent) {
    if (event.key === 'Enter' || event.key === ' ') {
      event.preventDefault();
      navigateTo('home');
    }
  }
</script>

<!-- Header Container -->
<div class="header-container" class:white-header={backgroundColor === 'white'}>
  <div class="header-content">
    <!-- Top section with 80/20 split -->
    <div class="top-link">
      <div class="top-left-section">
        <!-- 80% empty green section -->
      </div>
      <div class="top-right-section">
        <a href="https://singforhope.org" target="_blank" class="site-link">
          <span>singforhope.org</span>
          <svg width="12" height="12" viewBox="0 0 12 12" fill="none">
            <path d="M3 9L9 3M9 3H3M9 3V9" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </a>
      </div>
    </div>

    <!-- Logo Section - positioned relative to entire header -->
    <div
      class="logo-section"
      on:click={handleLogoClick}
      on:keydown={handleLogoKeydown}
      role="button"
      tabindex="0"
      style="cursor: pointer;"
      aria-label="Go to home page"
    >
      <div class="sfh-logo">
        <img src="/others/Layer_1-2.svg" alt="Sing for Hope" class="sfh-logo-img" />
      </div>
      <div class="classroom-logo">
        <img src="/others/Classroom 1.svg" alt="Classroom" class="classroom-logo-img" />
      </div>
    </div>

    <!-- Main Navigation Header -->
    <div class="nav-header">
      <!-- Navigation content wrapper -->
      <div class="nav-content">
        <!-- Navigation Links -->
        <div class="nav-links">
          <button class="nav-link {currentPage === 'curriculum' ? 'active' : ''}" on:click={() => navigateTo('curriculum')}>
            Curriculum
          </button>
          <button class="nav-link {currentPage === 'about' ? 'active' : ''}" on:click={() => navigateTo('about')}>
            About
          </button>
        </div>

        <!-- Auth Section -->
        <div class="auth-section">
          {#if !isLoggedIn}
            <button class="sign-in-btn">Sign In</button>
          {:else}
            <button class="account-section" on:click={() => navigateTo('myaccount')}>
              <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                <circle cx="10" cy="7" r="3" stroke="white" stroke-width="1.5"/>
                <path d="M4 18c0-3.314 2.686-6 6-6s6 2.686 6 6" stroke="white" stroke-width="1.5"/>
              </svg>
              <span>My Account</span>
            </button>
          {/if}
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Spacer to push content below fixed header -->
<div class="header-spacer"></div>

<style>
  .header-container {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    width: 100%;
    background: rgba(253, 249, 241, 0.95);
    backdrop-filter: blur(10px);
    z-index: 1000;
    padding: 20px;
    box-sizing: border-box;
  }

  .header-content {
    max-width: 1200px;
    margin: 0 auto;
    position: relative;
  }

  .header-spacer {
    height: 160px; /* Adjust based on header height */
  }

  /* Top Link */
  .top-link {
    display: flex;
    margin-bottom: 0;
    background: #349552;
    border-radius: 20px 20px 0 0;
    margin-left: 20px;
    margin-right: 20px;
    overflow: hidden;
  }

  .top-left-section {
    flex: 0 0 80%;
    background: #349552;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    position: relative;
    z-index: 1;
  }

  .top-right-section {
    flex: 0 0 20%;
    background: var(--SFH-Cream, #FDF9F1);
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 10px;
    border-top-right-radius: 20px;
    border-bottom-left-radius: 20px;
  }

  .site-link {
    display: flex;
    align-items: center;
    gap: 4px;
    color: #333;
    text-decoration: none;
    font-size: 14px;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    transition: color 0.2s;
  }

  .site-link:hover {
    color: #349552;
  }

  /* Main Navigation Header */
  .nav-header {
    background: #349552;
    border-radius: 0 0 20px 20px;
    padding: 0 30px 30px 30px;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0 4px 20px rgba(52, 149, 82, 0.2);
    margin: 0 20px;
    position: relative;
  }

  /* Navigation content wrapper */
  .nav-content {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    position: relative;
  }

  /* Logo Section */
  .logo-section {
    display: flex;
    align-items: center;
    gap: 12px;
    position: absolute;
    left: 50px;
    top: 50%;
    transform: translateY(-50%);
    z-index: 10;
  }

  .sfh-logo {
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .sfh-logo-img {
    height: 60px;
    width: auto;
    filter: brightness(0) invert(1);
  }

  .classroom-logo {
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .classroom-logo-img {
    height: 30px;
    width: auto;
    filter: brightness(0) invert(1);
  }

  /* Navigation Links */
  .nav-links {
    display: flex;
    gap: 40px;
    padding: 0px 20px 10px 20px;
    align-items: flex-start;
  }

  .nav-link {
    color: white;
    background: none;
    border: none;
    font-size: 18px;
    font-weight: 400;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    transition: opacity 0.2s;
    position: relative;
    cursor: pointer;
    padding: 0;
  }

  .nav-link:hover,
  .nav-link.active {
    opacity: 0.8;
  }

  .nav-link.active::after {
    content: '';
    position: absolute;
    bottom: -8px;
    left: 0;
    right: 0;
    height: 2px;
    background: white;
    border-radius: 1px;
  }

  /* Auth Section */
  .auth-section {
    display: flex;
    align-items: center;
    position: absolute;
    right: 0;
    top: 50%;
    transform: translateY(-50%);
    padding: 40px 15px 15px 15px;
  }

  .sign-in-btn {
    background: rgba(255, 255, 255, 0.2);
    border: 1px solid rgba(255, 255, 255, 0.3);
    color: white;
    padding: 12px 24px;
    border-radius: 25px;
    font-size: 16px;
    font-weight: 500;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    cursor: pointer;
    transition: all 0.2s;
  }

  .sign-in-btn:hover {
    background: rgba(255, 255, 255, 0.3);
    transform: translateY(-1px);
  }

  .account-section {
    display: flex;
    align-items: center;
    gap: 8px;
    color: white;
    font-size: 16px;
    font-weight: 500;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    cursor: pointer;
    padding: 8px 16px;
    border-radius: 20px;
    transition: background 0.2s;
    background: none;
    border: none;
  }

  .account-section:hover {
    background: rgba(255, 255, 255, 0.1);
  }

  /* White background variant */
  .white-header .nav-header {
    background: white;
    border: 1px solid #e0e0e0;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
  }

  .white-header .nav-link {
    color: #333;
  }

  .white-header .nav-link.active::after {
    background: #349552;
  }

  .white-header .sign-in-btn {
    background: #349552;
    color: white;
    border: none;
  }

  .white-header .sign-in-btn:hover {
    background: #2a7a44;
  }

  .white-header .account-section {
    color: #333;
  }

  .white-header .account-section:hover {
    background: rgba(52, 149, 82, 0.1);
  }

  .white-header .account-section svg {
    stroke: #333;
  }

  .white-header .sfh-logo-img,
  .white-header .classroom-logo-img {
    filter: none;
  }

  /* Responsive Design */
  @media (max-width: 768px) {
    .header-container {
      padding: 15px;
    }

    .nav-header {
      padding: 15px 20px;
      flex-direction: column;
      gap: 20px;
    }

    .nav-links {
      gap: 30px;
    }


    .nav-link {
      font-size: 16px;
    }
  }

  @media (max-width: 480px) {
    .nav-header {
      flex-direction: column;
      gap: 15px;
    }

    .nav-links {
      gap: 20px;
    }

    .logo-section {
      gap: 8px;
    }


    .nav-link {
      font-size: 14px;
    }

    .sign-in-btn {
      padding: 8px 16px;
      font-size: 14px;
    }
  }
</style>