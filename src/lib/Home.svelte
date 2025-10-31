<script lang="ts">
  const goals = [
    { number: 1, title: "No Poverty", color: "#E5243B", textColor: "white", icon: "/About/about-goal-1.svg" },
    { number: 2, title: "Zero Hunger", color: "#DDA63A", textColor: "black", icon: "/About/about-goal-2.svg" },
    { number: 3, title: "Good Health & Wellbeing", color: "#4C9F38", textColor: "white", icon: "/About/about-goal-3.svg" },
    { number: 4, title: "Quality Education", color: "#C5192D", textColor: "white", icon: "/About/about-goal-4.svg" },
    { number: 5, title: "Gender Equality", color: "#FF3A21", textColor: "white", icon: "/About/about-goal-5.svg" },
    { number: 6, title: "Clean Water & Sanitation", color: "#26BDE2", textColor: "black", icon: "/About/about-goal-6.svg" },
    { number: 7, title: "Affordable & Clean Energy", color: "#F2BA44", textColor: "black", icon: "/About/about-goal-7.svg" },
    { number: 8, title: "Decent Work & Economic Growth", color: "#A21942", textColor: "white", wide: true, icon: "/About/about-goal-8.svg" },
    { number: 9, title: "Industry, Innovation & Infrastructure", color: "#FA6622", textColor: "white", icon: "/About/about-goal-9.svg" },
    { number: 10, title: "Reduced Inequalities", color: "#DD1367", textColor: "white", icon: "/About/about-goal-10.svg" },
    { number: 11, title: "Sustainable Cities & Communities", color: "#FD9D24", textColor: "black", icon: "/About/about-goal-11.svg" },
    { number: 12, title: "Responsible Consumption & Production", color: "#BF8B2E", textColor: "white", icon: "/About/about-goal-12.svg" },
    { number: 13, title: "Climate Action", color: "#3F7E44", textColor: "white", icon: "/About/about-goal-13.svg" },
    { number: 14, title: "Life Below Water", color: "#0A97D9", textColor: "white", icon: "/About/about-goal-14.svg" },
    { number: 15, title: "Life on Land", color: "#56C02B", textColor: "black", wide: true, icon: "/About/about-goal-15.svg" },
    { number: 16, title: "Peace, Justice & Strong Institutions", color: "#00689D", textColor: "white", narrow: true, icon: "/About/about-goal-16.svg" },
    { number: 17, title: "Partnerships for the Goals", color: "#19486A", textColor: "white", icon: "/About/about-goal-17.svg" }
  ];

  const subjects = [
    { name: "Creative Writing", image: "/Home/home-desktop-creative-writing.png" },
    { name: "Visual Art", image: "/Home/home-desktop-visual-art.png" },
    { name: "Dance & Movement", image: "/Home/home-desktop-dance-and-movement.png" },
    { name: "Music", image: "/Home/home-desktop-music.png" },
    { name: "Drama", image: "/Home/home-desktop-drama.png" }
  ];
</script>

<div class="home">
  <!-- Top Container with 80/20 split -->
  <div class="top-container">
    <div class="green-section">
      <!-- 80% green section -->
    </div>
    <div class="right-section">
      <a href="https://singforhope.org" target="_blank" class="site-link">
        singforhope.org ↗
      </a>
    </div>
  </div>

  <!-- Navigation Header -->
  <nav class="navigation-header">
    <div class="nav-content">
      <div class="logo">
        <img src="/others/Layer_1-2.svg" alt="Sing for Hope" class="logo-image sing-for-hope-logo" />
        <img src="/others/Classroom 1.svg" alt="Classroom" class="logo-image classroom-logo" />
      </div>
      
      <div class="nav-links">
        <a href="#curriculum">Curriculum</a>
        <a href="#about">About</a>
      </div>
      
      <div class="nav-actions">
        <button class="sign-in-btn">Sign In</button>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <img src="/Home/home-desktop-hero-animated.gif" alt="Hero Animation" class="hero-bg" />
    <div class="hero-content">
      <h1 class="hero-title">Inspire change through the arts.</h1>
      <p class="hero-subtitle">
        Empower the next generation with our accessible, fun, and ready-to-use 
        arts-based curriculum for grades 5-12.
      </p>
    </div>
  </section>

  <!-- Global Goals Section -->
  <section class="global-goals-section">
    <h2 class="section-title">Lessons by Goal</h2>
    <div class="goals-grid">
      {#each goals as goal}
        <div
          class="goal-card"
          class:wide={goal.wide}
          class:narrow={goal.narrow}
          style="background-color: {goal.color}; color: {goal.textColor};"
        >
          <div class="goal-header">
            <div class="goal-number">{goal.number}</div>
            <img src={goal.icon} alt="Goal {goal.number} icon" class="goal-icon" />
          </div>
          <div class="goal-title">{goal.title}</div>
        </div>
      {/each}
    </div>
  </section>

  <!-- Lessons by Subject Section -->
  <section class="subjects-section">
    <h2 class="section-title">Lessons by Subject</h2>
    <div class="subjects-grid">
      {#each subjects as subject}
        <div class="subject-card">
          <img src={subject.image} alt={subject.name} />
          <div class="subject-overlay">
            <h3>{subject.name}</h3>
          </div>
        </div>
      {/each}
    </div>
  </section>

  <!-- Lessons by Grade Section -->
  <section class="grades-section">
    <h2 class="section-title">Lessons by Grade</h2>
    <div class="grades-content">
      <div class="grade-options">
        <button class="grade-btn">Grades 5-8</button>
        <button class="grade-btn">Grades 9-12</button>
      </div>
      <div class="see-all-box">
        <span>See All Lessons</span>
        <span class="arrow">→</span>
      </div>
    </div>
  </section>

  <!-- FAQ Section -->
  <section class="faq-section">
    <div class="faq-bg">
      <img src="/Home/home-desktop-faq.png" alt="FAQ Background" />
    </div>
    <div class="faq-content">
      <h2 class="section-title">FAQ's</h2>
      <div class="faq-list">
        <div class="faq-item">
          <span>Who is this curriculum designed for?</span>
          <span class="faq-icon">▼</span>
        </div>
        <div class="faq-item">
          <span>How are the lessons structured?</span>
          <span class="faq-icon">▼</span>
        </div>
        <div class="faq-item">
          <span>Are there grade-specific versions of the lessons?</span>
          <span class="faq-icon">▼</span>
        </div>
        <div class="faq-item">
          <span>Is this curriculum free to use?</span>
          <span class="faq-icon">▼</span>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="footer-content">
      <div class="footer-column">
        <h3>Curriculum</h3>
        <div class="footer-section">
          <h4>By Subject</h4>
          <ul>
            <li>Visual Art</li>
            <li>Creative Writing</li>
            <li>Dance & Movement</li>
            <li>Music</li>
            <li>Drama</li>
          </ul>
        </div>
        <div class="footer-section">
          <h4>By Grade</h4>
          <ul>
            <li>Grades 5-8</li>
            <li>Grades 9-12</li>
          </ul>
        </div>
      </div>

      <div class="footer-column">
        <h4>By Global Goal</h4>
        <select class="goal-select">
          <option>Select a goal</option>
          {#each goals as goal}
            <option>Goal {goal.number}: {goal.title}</option>
          {/each}
        </select>
      </div>

      <div class="footer-column">
        <ul class="footer-links">
          <li><a href="#about">About</a></li>
          <li><a href="#contributors">Contributors</a></li>
        </ul>
      </div>

      <div class="footer-column sing-for-hope-box">
        <h3>Sing for Hope</h3>
        <p>
          Our creative programs bring hope, healing, and connection to millions 
          of people in hospitals, care facilities, schools, refugee camps, transit 
          hubs, and community spaces worldwide.
        </p>
        <button class="learn-more-btn">Learn more</button>
      </div>
    </div>
    
    <div class="footer-bottom">
      <p>Copyright ©2025 Sing for Hope, Inc. All rights reserved.</p>
    </div>
  </footer>
</div>

<style>
  @import '../styles/global.css';

  .home {
    width: 100%;
    min-height: 100vh;
    background: var(--SFH-Cream);
  }

  /* Top Container with 80/20 split */
  .top-container {
    display: flex;
    width: calc(100% - 160px);
    height: 50px;
    margin: 20px 80px 0 80px;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    overflow: hidden;
  }

  .green-section {
    flex: 0 0 80%;
    background: var(--SFH-Green);
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
  }

  .right-section {
    flex: 0 0 20%;
    background: var(--SFH-Cream);
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0 20px;
    border-top-right-radius: 20px;
    border-bottom-left-radius: 20px;
  }

  .right-section .site-link {
    color: black;
    text-decoration: none;
    font-size: 16px;
    padding: 8px 16px;
    transition: all 0.3s;
    white-space: nowrap;
    outline: none;
  }

  .right-section .site-link:hover {
    transform: scale(1.05);
  }

  .right-section .site-link:focus {
    outline: none;
  }

  /* Navigation */
  .navigation-header {
    background: var(--SFH-Green);
    padding: 0 0 20px 0;
    margin: 0 80px 0 80px;
    position: sticky;
    top: 0;
    z-index: 100;
    border-top-right-radius: 20px;
    border-bottom-right-radius: 20px;
    border-bottom-left-radius: 20px;
  }

  .nav-content {
    max-width: 1440px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .logo {
    display: flex;
    align-items: center;
    gap: 15px;
    position: relative;
    z-index: 10;
    padding-left: 40px;
  }

  .logo-image {
    height: 40px;
    width: auto;
    filter: brightness(0) invert(1);
  }

  .sing-for-hope-logo {
    height: 80px;
    transform: translateY(-20px);
  }

  .classroom-logo {
    height: 30px;
    transform: translateY(-20px);
  }

  .nav-links {
    display: flex;
    gap: 60px;
    transform: translateY(-20px);
  }

  .nav-links a {
    color: white;
    text-decoration: none;
    font-size: 16px;
    transition: opacity 0.3s;
  }

  .nav-links a:hover {
    opacity: 0.8;
  }

  .nav-actions {
    display: flex;
    gap: 30px;
    align-items: center;
    padding-right: 40px;
  }

  .site-link {
    color: white;
    text-decoration: none;
    font-size: 16px;
    padding: 8px 16px;
    background: rgba(255, 255, 255, 0.1);
    border-radius: 8px;
  }

  .sign-in-btn {
    background: white;
    color: var(--SFH-Green);
    border: none;
    padding: 12px 32px;
    border-radius: 25px;
    font-size: 18px;
    font-weight: 500;
    cursor: pointer;
    transition: transform 0.2s;
  }

  .sign-in-btn:hover {
    transform: scale(1.05);
  }

  /* Hero Section */
  .hero {
    position: relative;
    height: 500px;
    margin: 40px 80px;
    border-radius: 20px;
    overflow: hidden;
    box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
  }

  .hero-bg {
    width: 100%;
    height: 100%;
    object-fit: cover;
    position: absolute;
    top: 0;
    left: 0;
  }

  .hero-content {
    position: relative;
    z-index: 2;
    padding: 80px;
    max-width: 700px;
    background: linear-gradient(90deg, rgba(253, 249, 241, 0.95) 0%, rgba(253, 249, 241, 0.7) 70%, transparent 100%);
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .hero-title {
    font-size: 84px;
    font-weight: 400;
    line-height: 1.1;
    color: var(--SFH-Green);
    margin-bottom: 30px;
    text-shadow: 0 2px 10px rgba(255, 255, 255, 0.8);
  }

  .hero-subtitle {
    font-size: 24px;
    line-height: 1.4;
    color: var(--SFH-Black);
    background: rgba(255, 255, 255, 0.9);
    padding: 15px 20px;
    border-radius: 10px;
  }

  /* Sections */
  .section-title {
    font-size: 60px;
    font-weight: 400;
    line-height: 1.1;
    color: var(--SFH-Black);
    margin-bottom: 40px;
  }

  /* Global Goals */
  .global-goals-section {
    padding: 80px;
    max-width: 1440px;
    margin: 0 auto;
    background: white;
  }

  .goals-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(230px, 1fr));
    gap: 22px;
  }

  .goal-card {
    padding: 22px;
    border-radius: 20px;
    min-height: 167px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    transition: all 0.3s;
    cursor: pointer;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  }

  .goal-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
  }

  .goal-card.wide {
    grid-column: span 2;
  }

  .goal-card.narrow {
    grid-column: span 1;
  }

  .goal-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
  }

  .goal-number {
    font-size: 52px;
    font-weight: 400;
    line-height: 1;
  }

  .goal-icon {
    width: 60px;
    height: 60px;
    object-fit: contain;
  }

  .goal-title {
    font-size: 24px;
    font-weight: 500;
    line-height: 1.2;
    margin-top: 10px;
  }

  /* Subjects Section */
  .subjects-section {
    padding: 80px;
    max-width: 1440px;
    margin: 0 auto;
  }

  .subjects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 30px;
  }

  .subject-card {
    position: relative;
    border-radius: 20px;
    overflow: hidden;
    height: 300px;
    cursor: pointer;
  }

  .subject-card img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s;
  }

  .subject-card:hover img {
    transform: scale(1.1);
  }

  .subject-overlay {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    padding: 30px;
    background: linear-gradient(to top, rgba(0,0,0,0.85) 0%, rgba(0,0,0,0.4) 70%, transparent 100%);
  }

  .subject-overlay h3 {
    color: white;
    font-size: 48px;
    font-weight: 400;
    line-height: 1.1;
    text-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
  }

  /* Grades Section */
  .grades-section {
    padding: 80px;
    max-width: 1440px;
    margin: 0 auto;
    background: white;
  }

  .grades-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 40px;
  }

  .grade-options {
    display: flex;
    gap: 30px;
  }

  .grade-btn {
    font-size: 46px;
    font-weight: 300;
    background: none;
    border: none;
    color: var(--SFH-Black);
    cursor: pointer;
    padding: 10px 20px;
    transition: color 0.3s;
  }

  .grade-btn:hover {
    color: var(--SFH-Green);
  }

  .see-all-box {
    background: white;
    border: 2px solid var(--SFH-Black);
    border-radius: 20px;
    padding: 30px 50px;
    font-size: 48px;
    display: flex;
    align-items: center;
    gap: 20px;
    cursor: pointer;
    transition: all 0.3s;
  }

  .see-all-box:hover {
    background: var(--SFH-Green);
    color: white;
    border-color: var(--SFH-Green);
  }

  /* FAQ Section */
  .faq-section {
    position: relative;
    padding: 80px;
    min-height: 600px;
    max-width: 1440px;
    margin: 0 auto;
  }

  .faq-bg {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 0;
    opacity: 0.3;
  }

  .faq-bg img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .faq-content {
    position: relative;
    z-index: 1;
  }

  .faq-content .section-title {
    background: rgba(255, 255, 255, 0.95);
    display: inline-block;
    padding: 10px 30px;
    border-radius: 15px;
    margin-bottom: 40px;
  }

  .faq-list {
    display: flex;
    flex-direction: column;
    gap: 20px;
    max-width: 900px;
  }

  .faq-item {
    background: rgba(255, 255, 255, 0.98);
    padding: 30px;
    border-radius: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 24px;
    font-weight: 500;
    cursor: pointer;
    transition: all 0.3s;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  }

  .faq-item:hover {
    background: var(--SFH-Green);
    color: white;
    transform: translateX(10px);
    box-shadow: 0 4px 20px rgba(52, 149, 82, 0.3);
  .faq-icon {
    transition: transform 0.3s;
  }

  .faq-item:hover .faq-icon {
    transform: rotate(180deg);
  }
  }

  /* Footer */
  .footer {
    background: linear-gradient(180deg, rgba(52, 149, 82, 0.9) 0%, var(--SFH-Green) 100%);
    color: white;
    padding: 60px 80px 30px;
  }

  .footer-content {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 60px;
    margin-bottom: 40px;
  }

  .footer-column h3 {
    font-size: 30px;
    margin-bottom: 20px;
  }

  .footer-column h4 {
    font-size: 20px;
    font-weight: 500;
    margin: 20px 0 10px;
  }

  .footer-column ul {
    list-style: none;
    padding: 0;
  }

  .footer-column li {
    margin: 8px 0;
    font-size: 18px;
  }

  .footer-links {
    font-size: 24px;
  }

  .footer-links a {
    color: white;
    text-decoration: none;
  }

  .goal-select {
    width: 100%;
    padding: 15px;
    border-radius: 8px;
    border: none;
    font-size: 18px;
    background: white;
    color: var(--SFH-Black);
  }

  .sing-for-hope-box {
    background: white;
    color: var(--SFH-Black);
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
  }

  .sing-for-hope-box h3 {
    color: var(--SFH-Black);
    font-size: 28px;
    margin-bottom: 15px;
    font-weight: 600;
  }

  .sing-for-hope-box p {
    font-size: 18px;
    line-height: 1.6;
    margin-bottom: 20px;
    color: #333;
  }

  .learn-more-btn {
    background: var(--SFH-Green);
    color: white;
    border: none;
    padding: 12px 32px;
    border-radius: 25px;
    font-size: 18px;
    font-weight: 500;
    cursor: pointer;
    transition: transform 0.2s;
  }

  .learn-more-btn:hover {
    transform: scale(1.05);
  }

  .footer-bottom {
    text-align: center;
    padding-top: 30px;
    border-top: 1px solid rgba(255, 255, 255, 0.3);
    opacity: 0.7;
    font-size: 14px;
  }

  @media (max-width: 768px) {
    .navigation-header {
      padding: 15px 20px;
    }

    .nav-content {
      flex-direction: column;
      gap: 20px;
    }

    .hero {
      margin: 20px;
      height: 400px;
    }

    .hero-content {
      padding: 40px;
    }

    .hero-title {
      font-size: 48px;
    }

    .hero-subtitle {
      font-size: 18px;
    }

    .section-title {
      font-size: 40px;
    }

    .global-goals-section,
    .subjects-section,
    .grades-section,
    .faq-section,
    .footer {
      padding: 40px 20px;
    }

    .goals-grid {
      grid-template-columns: 1fr;
    }

    .goal-card.wide,
    .goal-card.narrow {
      grid-column: span 1;
    }

    .subjects-grid {
      grid-template-columns: 1fr;
    }

    .grades-content {
      flex-direction: column;
    }

    .grade-btn {
      font-size: 32px;
    }

    .see-all-box {
      font-size: 32px;
      padding: 20px 30px;
    }
  }
</style>