<script lang="ts">
  import Header from './Header.svelte';
  import Footer from './Footer.svelte';

  export let currentPage = 'home';
  export let navigateTo: (page: string) => void = () => {};

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
  <Header {currentPage} isLoggedIn={false} backgroundColor="green" {navigateTo} />

  <!-- Hero Section -->
  <div class="group-61">
    <div class="hero">
      <div class="rectangle-38"></div>
      <div class="inspire-change-through-the-arts"><span class="inspirechangethroughthearts_span">Inspire change through the arts.</span></div>
      <div class="empower-the-next-generation-with-our-accessible-fun-and-ready-to-use-arts-based-curriculum-for-grades-5-12"><span class="empowerthenextgenerationwithouraccessiblefunandready-to-usearts-basedcurriculumforgrades5-12_span">Empower the next generation with our accessible, fun, and ready-to-use arts-based curriculum for grades 5-12.</span></div>
    </div>
    <div class="header-art">
      <div class="frame-45">
        <div class="frame-138">
          <div class="vector"></div>
          <div class="vector_01"></div>
          <div class="vector_02"></div>
          <div class="vector_03"></div>
          <div class="vector_04"></div>
          <div class="vector_05"></div>
          <div class="vector_06"></div>
          <div class="vector_07"></div>
          <div class="vector_08"></div>
          <div class="vector_09"></div>
          <div class="vector_10"></div>
          <div class="vector_11"></div>
          <div class="vector_12"></div>
          <div class="vector_13"></div>
          <div class="vector_14"></div>
          <div class="vector_15"></div>
          <div class="vector_16"></div>
          <div class="vector_17"></div>
          <div class="vector_18"></div>
          <div class="vector_19"></div>
          <div class="vector_20"></div>
          <div class="vector_21"></div>
          <div class="vector_22"></div>
          <div class="vector_23"></div>
          <div class="vector_24"></div>
          <div class="vector_25"></div>
          <div class="vector_26"></div>
          <div class="vector_27"></div>
          <div class="vector_28"></div>
          <div class="vector_29"></div>
          <div class="vector_30"></div>
          <div class="vector_31"></div>
          <div class="vector_32"></div>
          <div class="vector_33"></div>
          <div class="vector_34"></div>
          <div class="vector_35"></div>
          <div class="vector_36"></div>
          <div class="vector_37"></div>
          <div class="vector_38"></div>
          <div class="vector_39"></div>
          <div class="vector_40"></div>
          <div class="vector_41"></div>
          <div class="vector_42"></div>
          <div class="vector_43"></div>
        </div>
        <div class="frame-139">
          <img class="image-1" src="/others/NCAS.png" alt="NCAS - National Coalition for Arts Standards" />
          <div class="rectangle-58"></div>
        </div>
      </div>
      <div class="rectangle-46"></div>
    </div>
  </div>

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
      <button class="see-all-box" on:click={() => navigateTo('curriculum')}>
        <span>See All Lessons</span>
        <span class="arrow">→</span>
      </button>
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

  <Footer {navigateTo} />
</div>

<style>
  @import '../styles/global.css';

  .home {
    width: 100%;
    min-height: 100vh;
    background: var(--SFH-Cream);
  }

  /* Removed duplicate header styles - now handled by Header component */

  /* Hero Section */
  .group-61 {
    width: 100%;
    max-width: 1440px;
    height: 511px;
    position: relative;
    margin: 40px auto;
    overflow: hidden;
  }

  .rectangle-38 {
    width: 100%;
    height: 100%;
    left: 0;
    top: 0;
    position: absolute;
    border-radius: 20px;
    background: var(--SFH-Cream, #FDF9F1);
  }

  .inspirechangethroughthearts_span {
    color: var(--SFH-Green, #349552);
    font-size: 84px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 75.60px;
    word-wrap: break-word;
  }

  .inspire-change-through-the-arts {
    width: 628px;
    max-width: calc(100% - 154px);
    height: 165.65px;
    left: 77px;
    top: 106.49px;
    position: absolute;
  }

  .empowerthenextgenerationwithouraccessiblefunandready-to-usearts-basedcurriculumforgrades5-12_span {
    color: var(--SFH-Black, black);
    font-size: 24px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 29.52px;
    word-wrap: break-word;
  }

  .empower-the-next-generation-with-our-accessible-fun-and-ready-to-use-arts-based-curriculum-for-grades-5-12 {
    width: 532px;
    max-width: calc(100% - 154px);
    height: 71px;
    left: 77px;
    top: 272.13px;
    position: absolute;
    justify-content: center;
    display: flex;
    flex-direction: column;
  }

  .hero {
    width: 100%;
    height: 100%;
    left: 0px;
    top: 0px;
    position: absolute;
  }

  .header-art {
    width: 511px;
    height: 511px;
    right: 0px;
    top: 0px;
    position: absolute;
  }

  .frame-45 {
    width: 511px;
    height: 511px;
    left: -0.50px;
    top: 0px;
    position: absolute;
  }

  .frame-138 {
    width: 196px;
    height: 130px;
    left: 315px;
    top: -0.09px;
    position: absolute;
    background: var(--SFH-Green, #349552);
    overflow: hidden;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    border-bottom-right-radius: 20px;
    border-bottom-left-radius: 10px;
  }

  .frame-139 {
    width: 196px;
    height: 130px;
    left: 0px;
    top: 380.56px;
    position: absolute;
    background: var(--SFH-Green, #349552);
    overflow: hidden;
    border-top-left-radius: 20px;
    border-top-right-radius: 10px;
    border-bottom-right-radius: 20px;
    border-bottom-left-radius: 20px;
  }

  .rectangle-46 {
    width: 196px;
    height: 196px;
    left: 534.50px;
    top: -0.17px;
    position: absolute;
    border-radius: 20px;
    background: var(--SFH-Cream, #FDF9F1);
  }

  .image-1 {
    width: 170px;
    height: 63.75px;
    left: 12.96px;
    top: 33.12px;
    position: absolute;
    z-index: 2;
    object-fit: contain;
  }

  .rectangle-58 {
    width: 149.93px;
    height: 87.36px;
    left: 33.03px;
    top: 24.74px;
    position: absolute;
    background: var(--SFH-White, white);
    z-index: 1;
  }

  /* Vector styles for decorative elements */
  .vector {
    width: 130px;
    height: 77.50px;
    left: 33px;
    top: 26.25px;
    position: absolute;
    background: white;
  }

  .vector_01 {
    width: 22.51px;
    height: 28.55px;
    left: 38.24px;
    top: 67.73px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_02 {
    width: 25.84px;
    height: 27.79px;
    left: 89.77px;
    top: 68.14px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_03 {
    width: 17.74px;
    height: 27.79px;
    left: 117.35px;
    top: 68.14px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_04 {
    width: 21.16px;
    height: 28.55px;
    left: 136.33px;
    top: 67.76px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_05 {
    width: 6.66px;
    height: 6.11px;
    left: 65.47px;
    top: 72.23px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_06 {
    width: 5.79px;
    height: 6.77px;
    left: 80.87px;
    top: 69.47px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_07 {
    width: 6.57px;
    height: 4.65px;
    left: 84.81px;
    top: 76.52px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_08 {
    width: 6.61px;
    height: 6.10px;
    left: 83.22px;
    top: 72.35px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_09 {
    width: 6.22px;
    height: 4.29px;
    left: 63.76px;
    top: 81.41px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_10 {
    width: 6.29px;
    height: 6.58px;
    left: 82.20px;
    top: 87.31px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_11 {
    width: 6.22px;
    height: 4.22px;
    left: 85.25px;
    top: 81.46px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_12 {
    width: 6.32px;
    height: 6.56px;
    left: 66.86px;
    top: 87.43px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_13 {
    width: 6.61px;
    height: 4.67px;
    left: 63.88px;
    top: 76.41px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_14 {
    width: 5.03px;
    height: 6.75px;
    left: 79.61px;
    top: 89.19px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_15 {
    width: 6.66px;
    height: 5.43px;
    left: 84.18px;
    top: 84.85px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_16 {
    width: 4.27px;
    height: 6.18px;
    left: 75.58px;
    top: 90.11px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_17 {
    width: 4.11px;
    height: 6.48px;
    left: 78.12px;
    top: 68.37px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_18 {
    width: 5.10px;
    height: 6.72px;
    left: 70.75px;
    top: 89.26px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_19 {
    width: 4.16px;
    height: 6.45px;
    left: 73.09px;
    top: 68.36px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_20 {
    width: 6.74px;
    height: 5.55px;
    left: 64.41px;
    top: 84.87px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_21 {
    width: 5.75px;
    height: 6.71px;
    left: 68.71px;
    top: 69.44px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_22 {
    width: 9.92px;
    height: 13.05px;
    left: 38.60px;
    top: 33.72px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_23 {
    width: 9.91px;
    height: 12.87px;
    left: 50.20px;
    top: 33.88px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_24 {
    width: 9.92px;
    height: 13.05px;
    left: 61.80px;
    top: 33.72px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_25 {
    width: 10.52px;
    height: 12.68px;
    left: 72.80px;
    top: 33.89px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_26 {
    width: 12.12px;
    height: 12.68px;
    left: 82.76px;
    top: 33.89px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_27 {
    width: 3.03px;
    height: 12.68px;
    left: 96.18px;
    top: 33.89px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_28 {
    width: 10.52px;
    height: 12.68px;
    left: 101.49px;
    top: 33.89px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_29 {
    width: 12.12px;
    height: 12.68px;
    left: 113.28px;
    top: 33.89px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_30 {
    width: 9.75px;
    height: 12.68px;
    left: 126.49px;
    top: 33.89px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_31 {
    width: 8.32px;
    height: 12.68px;
    left: 138.09px;
    top: 33.89px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_32 {
    width: 8.69px;
    height: 12.68px;
    left: 147.86px;
    top: 33.89px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_33 {
    width: 9.68px;
    height: 12.43px;
    left: 38.97px;
    top: 51.30px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_34 {
    width: 8.20px;
    height: 12.43px;
    left: 49.84px;
    top: 51.30px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_35 {
    width: 11.52px;
    height: 12.43px;
    left: 58.80px;
    top: 51.30px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_36 {
    width: 8.16px;
    height: 12.43px;
    left: 71.22px;
    top: 51.30px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_37 {
    width: 7.68px;
    height: 12.43px;
    left: 80.38px;
    top: 51.30px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_38 {
    width: 10.79px;
    height: 12.78px;
    left: 88.33px;
    top: 51.13px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_39 {
    width: 9.70px;
    height: 12.43px;
    left: 100.30px;
    top: 51.30px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_40 {
    width: 13.32px;
    height: 12.43px;
    left: 111.10px;
    top: 51.30px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_41 {
    width: 8.22px;
    height: 12.43px;
    left: 125.74px;
    top: 51.30px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_42 {
    width: 10.30px;
    height: 12.43px;
    left: 134.94px;
    top: 51.30px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_43 {
    width: 10.31px;
    height: 12.43px;
    left: 146.24px;
    top: 51.30px;
    position: absolute;
    background: var(--SFH-White, white);
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

  /* Removed duplicate footer styles - now handled by Footer component */

  @media (max-width: 768px) {
    .group-61 {
      width: 100%;
      height: 400px;
      margin: 20px auto;
      max-width: calc(100% - 40px);
    }

    .hero {
      width: 100%;
      height: 400px;
    }

    .rectangle-38 {
      width: 100%;
      height: 400px;
      left: 0;
      top: 0;
    }

    .inspire-change-through-the-arts {
      width: 90%;
      left: 5%;
      top: 80px;
    }

    .inspirechangethroughthearts_span {
      font-size: 48px;
      line-height: 50px;
    }

    .empower-the-next-generation-with-our-accessible-fun-and-ready-to-use-arts-based-curriculum-for-grades-5-12 {
      width: 90%;
      left: 5%;
      top: 200px;
    }

    .empowerthenextgenerationwithouraccessiblefunandready-to-usearts-basedcurriculumforgrades5-12_span {
      font-size: 18px;
      line-height: 22px;
    }

    .header-art {
      display: none;
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