<script>
  import { onMount } from 'svelte';
  import Header from './Header.svelte';
  import Footer from './Footer.svelte';
  
  export let currentPage;
  export let navigateTo;
  
  // Component logic will go here if needed
</script>

<div class="about-page">
  <Header {currentPage} isLoggedIn={false} backgroundColor="green" {navigateTo} />

  <!-- Page Title -->
  <div class="page-title-container">
    <h1 class="page-title">About</h1>
  </div>

  <!-- Main Content -->
  <div class="about-content">
    <!-- Hero Image -->
    <img class="hero-image" src="/About/about-desktop-hero.png" alt="About Hero" />

    <!-- Section 1 -->
    <div class="section-1">
      <div class="what-if-every-young-person-had-the-power-to-build-a-better-world">
        <span class="whatifeveryyoungpersonhadthepowertobuildabetterworld_span">
          What if every young person had the power to build a better world?
        </span>
      </div>
      
      <div class="header-copy">
        <div class="this-is-the-question-that-inspired-the-sing-for-hope-global-goals-arts-curriculum">
          <span class="thisisthequestionthatinspiredthesingforhopeglobalgoalsartscurriculum_span">
            This is the question that inspired the Sing for Hope Global Goals Arts Curriculum.
          </span>
        </div>
        <div class="the-united-nations-17-global-goals-for-sustainable-development-stand-as-a-powerful-blueprint-for-peace-and-prosperity-yet-they-presented-a-unique-opportunity-for-creative-engagement">
          <span class="theunitednations17globalgoalsforsustainabledevelopmentstandasapowerfulblueprintforpeaceandprosperityyettheypresentedauniqueopportunityforcreativeengagement_span">
            The United Nations' 17 Global Goals for Sustainable Development stand as a powerful blueprint for peace and prosperity, yet they presented a unique opportunity for creative engagement.
          </span>
        </div>
      </div>

      <!-- Goal Blocks -->
      <div class="goal-blocks">
        <!-- Goal 1 -->
        <div class="goal-1">
          <div data-goal="1" class="goal-icon">
            <img src="/About/about-goal-1.svg" alt="Goal 1: No Poverty" />
          </div>
        </div>
        
        <!-- Goal 2 -->
        <div class="goal-2">
          <div data-goal="2" class="goal-icon_01">
            <img src="/About/about-goal-2.svg" alt="Goal 2: Zero Hunger" />
          </div>
        </div>
        
        <!-- Goal 3 -->
        <div class="goal-3">
          <div data-goal="3" class="goal-icon_02">
            <img src="/About/about-goal-3.svg" alt="Goal 3: Good Health and Well-being" />
          </div>
        </div>
        
        <!-- Goal 4 -->
        <div class="goal-4">
          <div data-goal="4" class="goal-icon_03">
            <img src="/About/about-goal-4.svg" alt="Goal 4: Quality Education" />
          </div>
        </div>
        
        <!-- Goal 5 -->
        <div class="goal-5">
          <div data-goal="5" class="goal-icon_04">
            <img src="/About/about-goal-5.svg" alt="Goal 5: Gender Equality" />
          </div>
        </div>
        
        <!-- Goal 6 -->
        <div class="goal-6">
          <div data-goal="6" class="goal-icon_05">
            <img src="/About/about-goal-6.svg" alt="Goal 6: Clean Water and Sanitation" />
          </div>
        </div>
        
        <!-- Goal 7 -->
        <div class="goal-7">
          <div data-goal="7" class="goal-icon_06">
            <img src="/About/about-goal-7.svg" alt="Goal 7: Affordable and Clean Energy" />
          </div>
        </div>
        
        <!-- Goal 8 -->
        <div class="goal-8">
          <div data-goal="8" class="goal-icon_07">
            <img src="/About/about-goal-8.svg" alt="Goal 8: Decent Work and Economic Growth" />
          </div>
        </div>
        
        <!-- Goal 9 -->
        <div class="goal-9">
          <div data-goal="9" class="goal-icon_08">
            <img src="/About/about-goal-9.svg" alt="Goal 9: Industry, Innovation and Infrastructure" />
          </div>
        </div>
        
        <!-- Goal 10 -->
        <div class="goal-10">
          <div data-goal="10" class="goal-icon_09">
            <img src="/About/about-goal-10.svg" alt="Goal 10: Reduced Inequalities" />
          </div>
        </div>
        
        <!-- Goal 11 -->
        <div class="goal-11">
          <div data-goal="11" class="goal-icon_10">
            <img src="/About/about-goal-11.svg" alt="Goal 11: Sustainable Cities and Communities" />
          </div>
        </div>
        
        <!-- Goal 12 -->
        <div class="goal-12">
          <div data-goal="12" class="goal-icon_11">
            <img src="/About/about-goal-12.svg" alt="Goal 12: Responsible Consumption and Production" />
          </div>
        </div>
        
        <!-- Goal 13 -->
        <div class="goal-13">
          <div data-goal="13" class="goal-icon_12">
            <img src="/About/about-goal-13.svg" alt="Goal 13: Climate Action" />
          </div>
        </div>
        
        <!-- Goal 14 -->
        <div class="goal-14">
          <div data-goal="14" class="goal-icon_13">
            <img src="/About/about-goal-14.svg" alt="Goal 14: Life Below Water" />
          </div>
        </div>
        
        <!-- Goal 15 -->
        <div class="goal-15">
          <div data-goal="15" class="goal-icon_14">
            <img src="/About/about-goal-15.svg" alt="Goal 15: Life on Land" />
          </div>
        </div>
        
        <!-- Goal 16 -->
        <div class="goal-16">
          <div data-goal="16" class="goal-icon_15">
            <img src="/About/about-goal-16.svg" alt="Goal 16: Peace, Justice and Strong Institutions" />
          </div>
        </div>
        
        <!-- Goal 17 -->
        <div class="goal-17">
          <div data-goal="17" class="goal-icon_16">
            <img src="/About/about-goal-17.svg" alt="Goal 17: Partnerships for the Goals" />
          </div>
        </div>
      </div>

      <div class="copy">
        <span class="copy_span">
          With artists consistently at the forefront of movements for social justice and peace, it became clear that the Global Goals could be amplified by the universal language of the arts.
        </span>
      </div>
    </div>

    <!-- Text Subjects Section -->
    <div class="text-subjects">
      <div class="our-curriculum-was-born-from-this-conviction-to-give-a-creative-voice-to-the-global-goals-and-share-them-through-the-transformative-power-of-the-arts">
        <span class="ourcurriculumwasbornfromthisconvictiontogiveacreativevoicetotheglobalgoalsandsharethemthroughthetransformativepowerofthearts_span">
          Our curriculum was born from this conviction: to give a creative voice to the Global Goals and share them through the transformative power of the arts.
        </span>
      </div>
      <div class="subject-blocks">
        <div class="frame-1052">
          <div><span class="creativewriting_span">Creative Writing</span></div>
        </div>
        <div class="frame-1053">
          <div><span class="visualart_span">Visual Art</span></div>
        </div>
        <div class="frame-1054">
          <div><span class="drama_span">Drama</span></div>
        </div>
        <div class="frame-1055">
          <div><span class="music_span">Music</span></div>
        </div>
        <div class="frame-1056">
          <div><span class="dancemovement_span">Dance & Movement</span></div>
        </div>
      </div>
    </div>

    <!-- Image Blocks -->
    <div class="image-blocks">
      <img class="rectangle-65" src="/About/about-desktop-block-1.png" alt="About Block 1" />
      <img class="rectangle-61" src="/About/about-desktop-block-2.png" alt="About Block 2" />
      <img class="rectangle-72" src="/About/about-desktop-block-3.png" alt="About Block 3" />
    </div>

    <!-- Text Image Section -->
    <div class="text-image">
      <div class="the-sing-for-hope-global-goals-arts-curriculum-is-a-first-of-its-kind-free-digital-platform-that-empowers-students-in-grades-5-12-to-explore-urgent-global-issues-and-imagine-solutions-through-music-visual-art-creative-writing-dance-and-drama-designed-for-educators-worldwide-and-aligned-with-the-national-core-arts-standards-ncas-this-curriculum-is-more-than-a-resource-its-a-movement">
        <span class="thesingforhopeglobalgoalsartscurriculumisafirst-of-its-kindfreedigitalplatformthatempowersstudentsingrades5-12toexploreurgentglobalissuesandimaginesolutionsthroughmusicvisualartcreativewritingdanceanddramadesignedforeducatorsworldwideandalignedwiththenationalcoreartsstandardsncasthiscurriculumismorethanaresourceitsamovement_span">
          The Sing for Hope Global Goals Arts Curriculum is a first-of-its-kind, free digital platform that empowers students in grades 5-12 to explore urgent global issues and imagine solutions through music, visual art, creative writing, dance, and drama. Designed for educators worldwide and aligned with the National Core Arts Standards (NCAS), this Curriculum is more than a resource; it's a movement.
        </span>
      </div>
      <img class="image" src="/About/about-desktop-block-4.png" alt="About Block 4" />
    </div>

    <!-- Image Text Section -->
    <div class="image-text">
      <img class="rectangle-71" src="/About/about-desktop-block-5.png" alt="About Block 5" />
      <div class="across-the-initial-pilot-in-the-bronx-and-westchester-county-educators-who-embedded-the-global-goals-into-their-culture-through-the-arts-saw-fundamental-transformation-improved-behavior-higher-participation-and-stronger-attendance-why-when-students-see-their-creativity-linked-to-real-world-change-they-find-purpose-the-curriculum-channels-that-purpose-into-developing-the-skills-they-need-to-become-compassionate-leaders-and-advocates-for-a-better-world">
        <span class="acrosstheinitialpilotinthebronxandwestchestercountyeducatorswhoembeddedtheglobalgoalsintotheirculturethroughtheartssawfundamentaltransformationimprovedbehaviorhigherparticipationandstrongerattendancewhywhenstudentsseetheircreativitylinkedtoreal-worldchangetheyfindpurposethecurriculumchannelsthatpurposeintodevelopingtheskillstheyneedtobecomecompassionateleadersandadvocatesforabetterworld_span">
          Across the initial pilot in the Bronx and Westchester County, educators who embedded the Global Goals into their culture through the arts saw fundamental transformation: improved behavior, higher participation, and stronger attendance. Why? When students see their creativity linked to real-world change, they find purpose. The curriculum channels that purpose into developing the skills they need to become compassionate leaders and advocates for a better world.
        </span>
      </div>
    </div>

    <!-- Text Section -->
    <div class="text">
      <div class="the-curriculum-equips-young-people-with-the-creative-intellectual-and-socio-emotional-skills-they-need-to-become-compassionate-informed-global-citizens-powerful-advocates-for-positive-change-and-champions-for-sing-for-hopes-mission-of-creating-a-better-world-through-the-arts">
        <span class="thecurriculumequipsyoungpeoplewiththecreativeintellectualandsocio-emotionalskillstheyneedtobecomecompassionateinformedglobalcitizenspowerfuladvocatesforpositivechangeandchampionsforsingforhopesmissionofcreatingabetterworldthroughthearts_span">
          The Curriculum equips young people with the creative, intellectual, and socio-emotional skills they need to become compassionate, informed global citizens, powerful advocates for positive change, and champions for Sing for Hope's mission of "Creating a Better World Through the Arts."
        </span>
      </div>
    </div>

    <!-- Contributors Section -->
    <div class="contributors">
      <div class="text-button">
        <div class="header-copy_01">
          <div class="thank-you-to-our-contributors">
            <span class="thankyoutoourcontributors_span">Thank you to our contributors</span>
          </div>
          <div class="contributors-description">
            <span class="contributors-description_span">
              This curriculum was made possible through the generous support and collaboration of educators, artists, and advocates worldwide. Their dedication to empowering young people through arts education continues to inspire positive change in communities everywhere.
            </span>
          </div>
        </div>
        <div
          data-size="Large"
          data-state="Default"
          class="primary-button"
          on:click={() => navigateTo('contributors')}
          on:keydown={(e) => e.key === 'Enter' && navigateTo('contributors')}
          role="button"
          tabindex="0"
          style="cursor: pointer;"
          aria-label="Learn more about our contributors"
        >
          <div><span class="makeanaccount_span">Learn more</span></div>
        </div>
      </div>
    </div>

    <!-- Scrolling Text -->
    <div class="scrolling-text">
      <div class="scrolling-text_01">
        <span class="scrollingtext_01_span">Creating a Better World Through the Arts.</span>
      </div>
    </div>

    <!-- Large Button -->
    <div
      class="large-button"
      on:click={() => navigateTo('curriculum')}
      on:keydown={(e) => e.key === 'Enter' && navigateTo('curriculum')}
      role="button"
      tabindex="0"
      style="cursor: pointer;"
      aria-label="Browse curriculum"
    >
      <div><span class="browsecurriculum_span">Browse Curriculum</span></div>
      <div class="vector-2010"></div>
    </div>

  </div>

  <Footer {navigateTo} />
</div>

<style>
  @import '../styles/global.css';

  /* Override any Svelte-generated classes that might add unwanted spacing */
  :global(.s-XsEmFtvddWTw) {
    margin: 0 !important;
    padding: 0 !important;
  }

  .about-page {
    width: 100%;
    min-height: 100vh;
    background: var(--SFH-Cream, #FDF9F1);
  }

  /* Page Title */
  .page-title-container {
    padding: 40px 80px 60px;
    margin-top: 0;
    background: var(--SFH-Cream, #FDF9F1);
  }

  .page-title {
    color: var(--SFH-Green, #349552);
    font-size: 60px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 60px;
    margin: 0;
    text-align: center;
    max-width: 1200px;
    margin-left: auto;
    margin-right: auto;
  }

  .about-content {
    width: 100%;
    max-width: 1440px;
    margin: 0 auto;
    padding: 0 80px 80px;
    background: var(--SFH-Cream, #FDF9F1);
  }

  /* Import all the provided CSS styles */
  .signin_span {
    color: var(--SFH-White, white);
    font-size: 20px;
    font-family: Founders Grotesk;
    font-weight: 500;
    line-height: 24px;
    word-wrap: break-word;
  }

  .sign-in {
    left: 1194.60px;
    top: 63.02px;
    position: absolute;
  }

  .singforhopeorg_span {
    color: var(--SFH-Black, black);
    font-size: 16px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 19.20px;
    word-wrap: break-word;
  }

  .singforhopeorg {
    text-align: center;
  }

  .curriculum_span {
    color: var(--SFH-White, white);
    font-size: 20px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 24px;
    word-wrap: break-word;
  }

  .about_span {
    color: var(--SFH-White, white);
    font-size: 20px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 24px;
    word-wrap: break-word;
  }

  .vector {
    width: 10.42px;
    height: 16.57px;
    left: 14.95px;
    top: 41.77px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_01 {
    width: 12.48px;
    height: 12.56px;
    left: 28.16px;
    top: 46.08px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_02 {
    width: 12.45px;
    height: 16.63px;
    left: 43.78px;
    top: 46.07px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_03 {
    width: 12.33px;
    height: 12.56px;
    left: 58.51px;
    top: 46.07px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_04 {
    width: 3.33px;
    height: 9.74px;
    left: 48.86px;
    top: 34.56px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_05 {
    width: 7.20px;
    height: 7.24px;
    left: 52.75px;
    top: 37.22px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_06 {
    width: 3.48px;
    height: 7.07px;
    left: 60.99px;
    top: 37.22px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_07 {
    width: 5.54px;
    height: 9.74px;
    left: 17.56px;
    top: 27.41px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_08 {
    width: 1.96px;
    height: 13.07px;
    left: 24.54px;
    top: 23.84px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_09 {
    width: 8.08px;
    height: 9.49px;
    left: 28.50px;
    top: 27.41px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_10 {
    width: 9.65px;
    height: 13.12px;
    left: 37.87px;
    top: 27.41px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_11 {
    width: 85.13px;
    height: 85.87px;
    left: 0px;
    top: 0px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_12 {
    width: 9.90px;
    height: 11.92px;
    left: 88.96px;
    top: 9.26px;
    position: absolute;
  }

  .vector_13 {
    width: 9.90px;
    height: 11.92px;
    left: 105.97px;
    top: 9.26px;
    position: absolute;
  }

  .vector_14 {
    width: 7.57px;
    height: 6px;
    left: 31.86px;
    top: 15.28px;
    position: absolute;
  }

  .vector_15 {
    width: 21.54px;
    height: 23.49px;
    left: 0px;
    top: -0.01px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_16 {
    width: 2.97px;
    height: 22.60px;
    left: 23.71px;
    top: 0.43px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_17 {
    width: 16.01px;
    height: 16.54px;
    left: 28.89px;
    top: 6.92px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_18 {
    width: 13.59px;
    height: 16.55px;
    left: 45.50px;
    top: 6.91px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_19 {
    width: 13.59px;
    height: 16.55px;
    left: 60.53px;
    top: 6.91px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_20 {
    width: 9.65px;
    height: 16.12px;
    left: 76.48px;
    top: 6.93px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_21 {
    width: 16px;
    height: 16.55px;
    left: 85.92px;
    top: 6.93px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_22 {
    width: 16px;
    height: 16.55px;
    left: 102.93px;
    top: 6.93px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .vector_23 {
    width: 23.90px;
    height: 16.12px;
    left: 120.94px;
    top: 6.93px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .hero-image {
    width: 1283px;
    height: 336px;
    position: relative;
    border-radius: 20px;
  }

  .whatifeveryyoungpersonhadthepowertobuildabetterworld_span {
    color: var(--SFH-Green, #349552);
    font-size: 84px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 75.60px;
    word-wrap: break-word;
  }

  .what-if-every-young-person-had-the-power-to-build-a-better-world {
    width: 803.94px;
    height: 223.64px;
    text-align: center;
  }

  .thisisthequestionthatinspiredthesingforhopeglobalgoalsartscurriculum_span {
    color: var(--SFH-Black, black);
    font-size: 28px;
    font-family: Founders Grotesk;
    font-weight: 500;
    line-height: 28px;
    word-wrap: break-word;
  }

  .this-is-the-question-that-inspired-the-sing-for-hope-global-goals-arts-curriculum {
    align-self: stretch;
    height: 59px;
    text-align: center;
  }

  .theunitednations17globalgoalsforsustainabledevelopmentstandasapowerfulblueprintforpeaceandprosperityyettheypresentedauniqueopportunityforcreativeengagement_span {
    color: var(--SFH-Black, black);
    font-size: 24px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 31.20px;
    word-wrap: break-word;
  }

  .the-united-nations-17-global-goals-for-sustainable-development-stand-as-a-powerful-blueprint-for-peace-and-prosperity-yet-they-presented-a-unique-opportunity-for-creative-engagement {
    align-self: stretch;
    height: 102px;
    text-align: center;
  }

  .copy_span {
    color: var(--SFH-Black, black);
    font-size: 24px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 31.20px;
    word-wrap: break-word;
  }

  .copy {
    width: 634.16px;
    height: 102px;
    text-align: center;
  }

  .ourcurriculumwasbornfromthisconvictiontogiveacreativevoicetotheglobalgoalsandsharethemthroughthetransformativepowerofthearts_span {
    color: var(--SFH-Black, black);
    font-size: 24px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 31.20px;
    word-wrap: break-word;
  }

  .our-curriculum-was-born-from-this-conviction-to-give-a-creative-voice-to-the-global-goals-and-share-them-through-the-transformative-power-of-the-arts {
    width: 440.98px;
    height: 120px;
  }

  .creativewriting_span {
    color: var(--SFH-White, white);
    font-size: 32px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 32px;
    word-wrap: break-word;
  }

  .visualart_span {
    color: var(--SFH-White, white);
    font-size: 32px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 32px;
    word-wrap: break-word;
  }

  .drama_span {
    color: var(--SFH-White, white);
    font-size: 32px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 32px;
    word-wrap: break-word;
  }

  .music_span {
    color: var(--SFH-White, white);
    font-size: 32px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 32px;
    word-wrap: break-word;
  }

  .dancemovement_span {
    color: var(--SFH-White, white);
    font-size: 32px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 32px;
    word-wrap: break-word;
  }

  .rectangle-65 {
    width: 460px;
    height: 460px;
    left: 78px;
    top: 0px;
    position: absolute;
    border-radius: 20px;
  }

  .rectangle-61 {
    width: 198px;
    height: 167.25px;
    left: 947px;
    top: 292.75px;
    position: absolute;
    border-radius: 20px;
  }

  .rectangle-72 {
    width: 369px;
    height: 167.49px;
    left: 558px;
    top: 292.51px;
    position: absolute;
    border-radius: 20px;
  }

  .thesingforhopeglobalgoalsartscurriculumisafirst-of-its-kindfreedigitalplatformthatempowersstudentsingrades5-12toexploreurgentglobalissuesandimaginesolutionsthroughmusicvisualartcreativewritingdanceanddramadesignedforeducatorsworldwideandalignedwiththenationalcoreartsstandardsncasthiscurriculumismorethanaresourceitsamovement_span {
    color: var(--SFH-Black, black);
    font-size: 24px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 31.20px;
    word-wrap: break-word;
  }

  .the-sing-for-hope-global-goals-arts-curriculum-is-a-first-of-its-kind-free-digital-platform-that-empowers-students-in-grades-5-12-to-explore-urgent-global-issues-and-imagine-solutions-through-music-visual-art-creative-writing-dance-and-drama-designed-for-educators-worldwide-and-aligned-with-the-national-core-arts-standards-ncas-this-curriculum-is-more-than-a-resource-its-a-movement {
    width: 600px;
    height: 238px;
  }

  .image {
    width: 460px;
    height: 460px;
    position: relative;
    border-radius: 20px;
  }

  .rectangle-71 {
    width: 460px;
    height: 460px;
    border-radius: 20px;
  }

  .acrosstheinitialpilotinthebronxandwestchestercountyeducatorswhoembeddedtheglobalgoalsintotheirculturethroughtheartssawfundamentaltransformationimprovedbehaviorhigherparticipationandstrongerattendancewhywhenstudentsseetheircreativitylinkedtoreal-worldchangetheyfindpurposethecurriculumchannelsthatpurposeintodevelopingtheskillstheyneedtobecomecompassionateleadersandadvocatesforabetterworld_span {
    color: var(--SFH-Black, black);
    font-size: 24px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 31.20px;
    word-wrap: break-word;
  }

  .across-the-initial-pilot-in-the-bronx-and-westchester-county-educators-who-embedded-the-global-goals-into-their-culture-through-the-arts-saw-fundamental-transformation-improved-behavior-higher-participation-and-stronger-attendance-why-when-students-see-their-creativity-linked-to-real-world-change-they-find-purpose-the-curriculum-channels-that-purpose-into-developing-the-skills-they-need-to-become-compassionate-leaders-and-advocates-for-a-better-world {
    width: 600px;
    height: 250.08px;
  }

  .thecurriculumequipsyoungpeoplewiththecreativeintellectualandsocio-emotionalskillstheyneedtobecomecompassionateinformedglobalcitizenspowerfuladvocatesforpositivechangeandchampionsforsingforhopesmissionofcreatingabetterworldthroughthearts_span {
    color: var(--SFH-Black, black);
    font-size: 24px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 31.20px;
    word-wrap: break-word;
  }

  .the-curriculum-equips-young-people-with-the-creative-intellectual-and-socio-emotional-skills-they-need-to-become-compassionate-informed-global-citizens-powerful-advocates-for-positive-change-and-champions-for-sing-for-hopes-mission-of-creating-a-better-world-through-the-arts {
    width: 850px;
    height: 164px;
    left: 295px;
    top: 0.30px;
    position: absolute;
    text-align: center;
  }

  .thankyoutoourcontributors_span {
    color: var(--SFH-White, white);
    font-size: 48px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 43.20px;
    word-wrap: break-word;
  }

  .thank-you-to-our-contributors {
    align-self: stretch;
    text-align: center;
  }

  .loremipsumdolorsitametconsecteturadipiscingelitdonecmaximusturpisegetefficiturfacilisisphasellusvelhendreritestfringillaposuereestinidexinnislpellentesquerhoncusfringilla_span {
    color: var(--SFH-White, white);
    font-size: 18px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .contributors-description_span {
    color: var(--SFH-White, white);
    font-size: 18px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .contributors-description {
    align-self: stretch;
    text-align: center;
  }

  .makeanaccount_span {
    color: var(--SFH-White, white);
    font-size: 18px;
    font-family: Founders Grotesk;
    font-weight: 500;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .scrollingtext_01_span {
    color: var(--SFH-Green, #349552);
    font-size: 145px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 130.50px;
    word-wrap: break-word;
  }

  .scrolling-text_01 {
    width: 3062.60px;
    height: 170px;
    left: 0.02px;
    top: 23.50px;
    position: absolute;
  }

  .browsecurriculum_span {
    color: var(--SFH-Black, black);
    font-size: 48px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 43.20px;
    word-wrap: break-word;
  }

  .vector-2010 {
    width: 44.83px;
    height: 22.41px;
    transform: rotate(90deg);
    transform-origin: top left;
    outline: 4px var(--SFH-Black, black) solid;
    outline-offset: -2px;
  }

  /* Continue with all the other CSS classes... */
  /* Due to length constraints, I'll add the remaining styles in the next part */

  .frame-30 {
    left: 542px;
    top: 48.61px;
    position: absolute;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 59px;
    display: inline-flex;
  }

  .header-copy {
    width: 629.65px;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    gap: 12px;
    display: flex;
  }

  .frame-1052 {
    height: 88px;
    padding-top: 24px;
    padding-bottom: 24px;
    padding-left: 24px;
    padding-right: 62px;
    background: var(--SFH-Green, #349552);
    overflow: hidden;
    border-radius: 20px;
    justify-content: flex-start;
    align-items: center;
    gap: 10px;
    display: flex;
  }

  .frame-1053 {
    width: 179px;
    height: 88px;
    padding-top: 24px;
    padding-bottom: 24px;
    padding-left: 24px;
    padding-right: 45px;
    background: var(--17_Partnerships-for-the-Goals, #19486A);
    overflow: hidden;
    border-radius: 20px;
    justify-content: flex-start;
    align-items: center;
    gap: 10px;
    display: flex;
  }

  .frame-1054 {
    width: 146px;
    height: 88px;
    padding-top: 24px;
    padding-bottom: 24px;
    padding-left: 24px;
    padding-right: 13px;
    background: var(--10_Reduced-Inequalities, #DD1367);
    overflow: hidden;
    border-radius: 20px;
    justify-content: flex-start;
    align-items: center;
    gap: 10px;
    display: flex;
  }

  .frame-1055 {
    width: 240px;
    height: 88px;
    padding-top: 24px;
    padding-bottom: 24px;
    padding-left: 24px;
    padding-right: 62px;
    background: var(--05_Gender-Equality, #FF3A21);
    overflow: hidden;
    border-radius: 20px;
    justify-content: flex-start;
    align-items: center;
    gap: 10px;
    display: flex;
  }

  .frame-1056 {
    width: 382px;
    height: 88px;
    padding-top: 24px;
    padding-bottom: 24px;
    padding-left: 24px;
    padding-right: 62px;
    background: var(--06_Clean-Water, #26BDE2);
    overflow: hidden;
    border-radius: 20px;
    justify-content: flex-start;
    align-items: center;
    gap: 10px;
    display: flex;
  }

  .text {
    align-self: stretch;
    height: 164px;
    position: relative;
  }

  .header-copy_01 {
    align-self: stretch;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    gap: 12px;
    display: flex;
  }

  .primary-button {
    height: 44px;
    padding-top: 5px;
    padding-bottom: 8px;
    padding-left: 24px;
    padding-right: 24px;
    background: var(--SFH-Green, #349552);
    border-radius: 40px;
    justify-content: center;
    align-items: center;
    gap: 10px;
    display: inline-flex;
  }

  .scrolling-text {
    align-self: stretch;
    height: 193px;
    position: relative;
    overflow: hidden;
  }

  .large-button {
    width: 600.50px;
    padding: 48px;
    background: var(--SFH-White, white);
    overflow: hidden;
    border-radius: 20px;
    outline: 1.50px var(--SFH-Black, black) solid;
    outline-offset: -1.50px;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .logo {
    width: 244.11px;
    height: 85.87px;
    left: 30.75px;
    top: 14.80px;
    position: absolute;
  }

  .goal-1 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--01_No-Poverty-, #E5243B);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-2 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--02_Zero-Hunger, #DDA63A);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-3 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--03_Good-Health-and-Wellbeing, #4C9F38);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-4 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--04_Quality-Education, #C5192D);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-5 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--05_Gender-Equality, #FF3A21);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-6 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--06_Clean-Water, #26BDE2);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-7 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--07_Affordable-and-Clean-Energy, #F2BA44);
    overflow: hidden;
    border-radius: 20px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-8 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--08_Decent-Work, #A21942);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-9 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--09_Industry-Innovation-Infrastructure, #FA6622);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-10 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--10_Reduced-Inequalities, #DD1367);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-11 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--11_Sustainable-Cities, #FD9D24);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-12 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--12_Responsible-Consumption, #BF8B2E);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-13 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--13_Climate-Action, #3F7E44);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-14 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--14_Life-Below-Water, #0A97D9);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-15 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--15_Life-on-Land, #56C02B);
    overflow: hidden;
    border-radius: 17.74px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-16 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--16_Peace-Justice-Strong, #00689D);
    overflow: hidden;
    border-radius: 17.54px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .goal-17 {
    width: 89.20px;
    height: 89.20px;
    padding-left: 16.22px;
    padding-right: 16.22px;
    padding-top: 15px;
    padding-bottom: 15px;
    background: var(--17_Partnerships-for-the-Goals, #19486A);
    overflow: hidden;
    border-radius: 17.93px;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  /* Add remaining layout classes */
  .navigation-header {
    align-self: stretch;
    height: 188px;
    position: relative;
  }

  .navigation-headerfooter {
    align-self: stretch;
    height: 531px;
    position: relative;
    background: linear-gradient(360deg, rgba(2.02, 56.75, 2.02, 0.60) 0%, rgba(52, 152, 70, 0) 100%), var(--SFH-Green, #349552);
    overflow: hidden;
  }

  .goal-blocks {
    width: 911px;
    justify-content: center;
    align-items: flex-start;
    gap: 10px;
    display: inline-flex;
    flex-wrap: wrap;
    align-content: flex-start;
  }

  .section-1 {
    width: 883px;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    gap: 40px;
    display: flex;
  }

  .about-content {
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    gap: 80px;
    display: flex;
  }

  .text-subjects {
    align-self: stretch;
    padding-left: 160px;
    padding-right: 80px;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .subject-blocks {
    width: 632px;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 10px;
    display: flex;
    flex-wrap: wrap;
    align-content: flex-start;
  }

  .image-blocks {
    align-self: stretch;
    height: 460px;
    position: relative;
    overflow: hidden;
  }

  .text-image {
    align-self: stretch;
    padding-left: 160px;
    padding-right: 80px;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .image-text {
    align-self: stretch;
    padding-left: 80px;
    padding-right: 160px;
    justify-content: space-between;
    align-items: center;
    display: inline-flex;
  }

  .contributors {
    width: 845px;
    padding: 60px;
    background: var(--SFH-Dark-Green, #1A562C);
    overflow: hidden;
    border-radius: 20px;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 10px;
    display: flex;
  }

  .text-button {
    align-self: stretch;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    gap: 24px;
    display: flex;
  }

  /* Goal icon containers */
  .goal-icon img,
  .goal-icon_01 img,
  .goal-icon_02 img,
  .goal-icon_03 img,
  .goal-icon_04 img,
  .goal-icon_05 img,
  .goal-icon_06 img,
  .goal-icon_07 img,
  .goal-icon_08 img,
  .goal-icon_09 img,
  .goal-icon_10 img,
  .goal-icon_11 img,
  .goal-icon_12 img,
  .goal-icon_13 img,
  .goal-icon_14 img,
  .goal-icon_15 img,
  .goal-icon_16 img {
    width: 100%;
    height: auto;
    max-width: 60px;
    max-height: 60px;
  }

  /* Add remaining footer styles */
  .curriculum_01_span,
  .about_01_span,
  .contributors_01_span {
    color: var(--SFH-White, white);
    font-size: 24px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 28.75px;
    word-wrap: break-word;
  }

  .bysubject_span,
  .bygrade_span,
  .byglobalgoal_span {
    color: var(--SFH-White, white);
    font-size: 20px;
    font-family: Founders Grotesk;
    font-weight: 500;
    line-height: 24px;
    word-wrap: break-word;
  }

  .visualart_01_span,
  .creativewriting_01_span,
  .dancemovement_01_span,
  .music_01_span,
  .drama_01_span,
  .grades5-8_span,
  .grades9-12_span {
    color: var(--SFH-White, white);
    font-size: 18px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .copyright2025singforhopeincallrightsreserved_span {
    color: rgba(255, 255, 255, 0.50);
    font-size: 14px;
    font-family: Proxima Nova;
    font-weight: 400;
    line-height: 16.77px;
    word-wrap: break-word;
  }

  .singforhope_span {
    color: var(--SFH-Black, black);
    font-size: 28px;
    font-family: Founders Grotesk;
    font-weight: 500;
    line-height: 28px;
    word-wrap: break-word;
  }

  .ourcreativeprogramsbringhopehealingandconnectiontomillionsofpeopleinhospitalscarefacilitiesschoolsrefugeecampstransithubsandcommunityspacesworldwide_span {
    color: var(--SFH-Black, black);
    font-size: 18px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .makeanaccount_01_span {
    color: var(--SFH-White, white);
    font-size: 18px;
    font-family: Founders Grotesk;
    font-weight: 500;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .selectagoal_span {
    color: var(--SFH-Black, black);
    font-size: 18px;
    font-family: Founders Grotesk;
    font-weight: 400;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  /* Add positioning for footer elements */
  .curriculum_01 {
    width: 194.85px;
    left: 78px;
    top: 77.76px;
    position: absolute;
  }

  .about_01 {
    width: 194.85px;
    left: 293.13px;
    top: 258.76px;
    position: absolute;
  }

  .contributors_01 {
    width: 194.85px;
    left: 295px;
    top: 296.26px;
    position: absolute;
  }

  .by-subject {
    width: 114.31px;
    left: 78px;
    top: 136.76px;
    position: absolute;
  }

  .by-grade {
    width: 114.31px;
    left: 78px;
    top: 313.26px;
    position: absolute;
  }

  .by-global-goal {
    width: 133px;
    left: 295px;
    top: 136.76px;
    position: absolute;
  }

  .frame-74 {
    width: 151.50px;
    left: 78px;
    top: 163.76px;
    position: absolute;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 3px;
    display: inline-flex;
  }

  .frame-77 {
    width: 151.50px;
    left: 78px;
    top: 340.26px;
    position: absolute;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 3px;
    display: inline-flex;
  }

  .copyright-2025-sing-for-hope-inc-all-rights-reserved {
    width: 509.43px;
    left: 78px;
    top: 452.42px;
    position: absolute;
  }

  .frame-80 {
    width: 631px;
    padding-left: 28px;
    padding-right: 28px;
    padding-top: 29px;
    padding-bottom: 29px;
    left: 729px;
    top: 78.26px;
    position: absolute;
    background: var(--SFH-White, white);
    border-radius: 15px;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    gap: 10px;
    display: inline-flex;
  }

  .frame-79 {
    width: 385px;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 39px;
    display: flex;
  }

  .frame-82 {
    width: 385px;
    height: 123px;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 5px;
    display: flex;
  }

  .primary-button_01 {
    height: 44px;
    padding-top: 5px;
    padding-bottom: 8px;
    padding-left: 24px;
    padding-right: 24px;
    background: var(--SFH-Green, #349552);
    border-radius: 40px;
    justify-content: center;
    align-items: center;
    gap: 10px;
    display: inline-flex;
  }

  .frame-83 {
    width: 347px;
    height: 49px;
    left: 295px;
    top: 173.26px;
    position: absolute;
    background: var(--SFH-White, white);
    overflow: hidden;
    border-radius: 8px;
  }

  .select-a-goal {
    width: 251px;
    left: 17px;
    top: 12.91px;
    position: absolute;
  }

  .vector-24 {
    width: 12.57px;
    height: 6.83px;
    left: 312.43px;
    top: 24.09px;
    position: absolute;
    outline: 2.50px var(--SFH-Black, black) solid;
    outline-offset: -1.25px;
  }

  .image-1 {
    width: 175.64px;
    height: 65.87px;
    left: 1211.20px;
    top: 374.07px;
    position: absolute;
  }

  .rectangle-58 {
    width: 135.21px;
    height: 65.87px;
    left: 1231.94px;
    top: 377.17px;
    position: absolute;
    background: var(--SFH-White, white);
  }

  .frame-123 {
    width: 127.50px;
    height: 29.42px;
    left: 1122.62px;
    top: -5.44px;
    position: absolute;
    justify-content: flex-start;
    align-items: center;
    gap: 14.71px;
    display: inline-flex;
  }

  .logos {
    width: 85.14px;
    height: 85.87px;
    left: -0.49px;
    top: 0px;
    position: absolute;
    overflow: hidden;
  }

  .classroom-1 {
    width: 144.83px;
    height: 23.47px;
    left: 96.58px;
    top: 31.20px;
    position: absolute;
    overflow: hidden;
  }

  .logos_01 {
    width: 125px;
    height: 126.08px;
    left: 465.99px;
    top: 30px;
    position: absolute;
    overflow: hidden;
  }

  .frame-137 {
    width: 1283px;
    height: 115.56px;
    left: 78.50px;
    top: 72.48px;
    position: absolute;
  }

  .our-creative-programs-bring-hope-healing-and-connection-to-millions-of-people-in-hospitals-care-facilities-schools-refugee-camps-transit-hubs-and-community-spaces-worldwide {
    width: 385px;
    height: 110px;
  }

  /* Layout improvements */
  .section-1 {
    align-items: center;
    text-align: center;
    margin: 0 auto;
  }

  .text-subjects {
    align-items: center;
    text-align: center;
  }

  .text-image {
    align-items: center;
    text-align: left;
  }

  .image-text {
    align-items: center;
    text-align: left;
  }

  .contributors {
    margin: 0 auto;
    text-align: center;
  }

  .scrolling-text {
    text-align: center;
  }

  .large-button {
    margin: 0 auto;
    text-align: center;
  }

  /* Remove extra spacing */
  .frame-1073 {
    gap: 40px;
    padding-top: 0;
  }

  .goal-blocks {
    margin: 0 auto;
    max-width: 911px;
  }

  /* Responsive adjustments */
  @media (max-width: 1200px) {
    .page-title-container {
      padding: 40px 60px 50px;
    }

    .about-content {
      padding: 0 60px 60px;
      gap: 60px;
    }
  }

  @media (max-width: 968px) {
    .page-title-container {
      padding: 40px 30px 40px;
    }

    .page-title {
      font-size: 52px;
      line-height: 56px;
    }

    .about-content {
      padding: 0 30px 60px;
      gap: 50px;
    }

    .text-subjects,
    .text-image,
    .image-text {
      flex-direction: column;
      padding: 0;
      gap: 40px;
    }
  }

  @media (max-width: 768px) {
    .page-title-container {
      padding: 40px 20px 30px;
    }

    .page-title {
      font-size: 44px;
      line-height: 48px;
    }

    .about-content {
      padding: 0 20px 50px;
      gap: 40px;
    }

    .hero-image {
      width: 100%;
      height: auto;
    }

    .whatifeveryyoungpersonhadthepowertobuildabetterworld_span {
      font-size: 48px;
      line-height: 44px;
    }

    .goal-blocks {
      width: 100%;
      justify-content: center;
    }

    .text-subjects,
    .text-image,
    .image-text {
      flex-direction: column;
      padding: 0;
      gap: 30px;
    }

    .image-blocks {
      height: auto;
    }

    .rectangle-65,
    .rectangle-61,
    .rectangle-72,
    .image,
    .rectangle-71 {
      position: relative;
      width: 100%;
      max-width: 460px;
      height: auto;
      left: 0;
      top: 0;
      margin: 0 auto;
    }
  }

  @media (max-width: 480px) {
    .page-title-container {
      padding: 40px 16px 25px;
    }

    .page-title {
      font-size: 36px;
      line-height: 40px;
    }

    .about-content {
      padding: 0 16px 40px;
      gap: 30px;
    }
  }
</style>