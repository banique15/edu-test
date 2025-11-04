<script lang="ts">
  import { onMount } from 'svelte';
  import Header from './Header.svelte';
  import Footer from './Footer.svelte';

  export let currentPage = 'curriculum';
  export let navigateTo: (page: string) => void = () => {};

  // Sample lesson data - in a real app this would come from an API
  let lessons = [
    {
      id: 1,
      title: "Intro to Goal 2",
      description: "Explore Goal 2: Zero Hunger through creative writing.",
      sdgGoal: "2. Zero Hunger",
      subject: "Creative Writing",
      gradeLevel: ["Grades 5-8", "Grades 9-12"],
      isFavorited: false,
      goalColor: "#DDA63A"
    },
    {
      id: 2,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "2. Zero Hunger",
      subject: "Creative Writing",
      gradeLevel: ["Grades 5-8"],
      isFavorited: false,
      goalColor: "#DDA63A"
    },
    {
      id: 3,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "2. Zero Hunger",
      subject: "Creative Writing",
      gradeLevel: ["Grades 5-8"],
      isFavorited: false,
      goalColor: "#DDA63A"
    },
    {
      id: 4,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "2. Zero Hunger",
      subject: "Visual Art",
      gradeLevel: ["Grades 9-12"],
      isFavorited: false,
      goalColor: "#DDA63A"
    },
    {
      id: 5,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "2. Zero Hunger",
      subject: "Visual Art",
      gradeLevel: ["Grades 5-8"],
      isFavorited: false,
      goalColor: "#DDA63A"
    },
    {
      id: 6,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "2. Zero Hunger",
      subject: "Music",
      gradeLevel: ["Grades 9-12"],
      isFavorited: false,
      goalColor: "#DDA63A"
    },
    {
      id: 7,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "2. Zero Hunger",
      subject: "Music",
      gradeLevel: ["Grades 5-8"],
      isFavorited: false,
      goalColor: "#DDA63A"
    },
    {
      id: 8,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "2. Zero Hunger",
      subject: "Drama",
      gradeLevel: ["Grades 9-12"],
      isFavorited: false,
      goalColor: "#DDA63A"
    },
    {
      id: 9,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "2. Zero Hunger",
      subject: "Drama",
      gradeLevel: ["Grades 5-8"],
      isFavorited: false,
      goalColor: "#DDA63A"
    },
    {
      id: 10,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "1. No Poverty",
      subject: "Creative Writing",
      gradeLevel: ["Grades 5-8"],
      isFavorited: false,
      goalColor: "#E5243B"
    },
    {
      id: 11,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "1. No Poverty",
      subject: "Creative Writing",
      gradeLevel: ["Grades 9-12"],
      isFavorited: false,
      goalColor: "#E5243B"
    },
    {
      id: 12,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "1. No Poverty",
      subject: "Visual Art",
      gradeLevel: ["Grades 5-8"],
      isFavorited: false,
      goalColor: "#E5243B"
    },
    {
      id: 13,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "1. No Poverty",
      subject: "Visual Art",
      gradeLevel: ["Grades 9-12"],
      isFavorited: false,
      goalColor: "#E5243B"
    },
    {
      id: 14,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "1. No Poverty",
      subject: "Music",
      gradeLevel: ["Grades 5-8"],
      isFavorited: false,
      goalColor: "#E5243B"
    },
    {
      id: 15,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "1. No Poverty",
      subject: "Music",
      gradeLevel: ["Grades 9-12"],
      isFavorited: false,
      goalColor: "#E5243B"
    },
    {
      id: 16,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "1. No Poverty",
      subject: "Drama",
      gradeLevel: ["Grades 5-8"],
      isFavorited: false,
      goalColor: "#E5243B"
    },
    {
      id: 17,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "1. No Poverty",
      subject: "Drama",
      gradeLevel: ["Grades 5-12"],
      isFavorited: false,
      goalColor: "#E5243B"
    },
    {
      id: 18,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "1. No Poverty",
      subject: "Dance & Movement",
      gradeLevel: ["Grades 5-8"],
      isFavorited: false,
      goalColor: "#E5243B"
    },
    {
      id: 19,
      title: "Lesson title lorem ipsum",
      description: "Lorem ipsum dolor sit amet, consectetur adip",
      sdgGoal: "1. No Poverty",
      subject: "Dance & Movement",
      gradeLevel: ["Grades 9-12"],
      isFavorited: false,
      goalColor: "#E5243B"
    },
    {
      id: 20,
      title: "Intro to Goal 1",
      description: "Explore Goal 1: No Poverty through drama.",
      sdgGoal: "1. No Poverty",
      subject: "Drama",
      gradeLevel: ["Grades 5-8", "Grades 9-12"],
      isFavorited: false,
      goalColor: "#E5243B"
    }
  ];

  let savedLessons = [
    {
      id: 101,
      title: "Fluid Expressions",
      description: "Painting our vision for clean water",
      sdgGoal: "6. Clean Water & Sanitization",
      subject: "Visual Art",
      gradeLevel: ["Grades 5-8"],
      isFavorited: true,
      goalColor: "#26BDE2"
    },
    {
      id: 102,
      title: "Emotions in Color",
      description: "Painting for fairness and equality",
      sdgGoal: "5. Gender Equality",
      subject: "Visual Art",
      gradeLevel: ["Grades 5-8"],
      isFavorited: true,
      goalColor: "#FF3A21"
    },
    {
      id: 103,
      title: "Light Up Our World",
      description: "Building energy art for everyone",
      sdgGoal: "7. Affordable Clean Energy",
      subject: "Visual Art",
      gradeLevel: ["Grades 5-8"],
      isFavorited: true,
      goalColor: "#F2BA44"
    },
    {
      id: 104,
      title: "Optical Wonders",
      description: "Art for great jobs and a growing world",
      sdgGoal: "8. Decent Work & Economic Growth",
      subject: "Music",
      gradeLevel: ["Grades 9-12"],
      isFavorited: true,
      goalColor: "#A21942"
    }
  ];

  // Filter states
  let searchQuery = '';
  let selectedGradeLevel = 'All';
  let selectedSubject = 'All';
  let selectedSDGGoal = 'All';

  // Filter options
  const gradeLevels = ['All', '5-8', '9-12'];
  const subjects = ['All', 'Visual Art', 'Creative Writing', 'Dance & Movement', 'Drama', 'Music'];
  const sdgGoals = [
    'All', '1. No Poverty', '2. Zero Hunger', '3. Good Health and Well-being',
    '4. Quality Education', '5. Gender Equality', '6. Clean Water and Sanitation',
    '7. Affordable and Clean Energy', '8. Decent Work and Economic Growth',
    '9. Industry, Innovation and Infrastructure', '10. Reduced Inequalities',
    '11. Sustainable Cities and Communities', '12. Responsible Consumption and Production',
    '13. Climate Action', '14. Life Below Water', '15. Life on Land',
    '16. Peace, Justice and Strong Institutions', '17. Partnerships for the Goals'
  ];

  // Filter functions
  $: filteredLessons = lessons.filter(lesson => {
    const matchesSearch = searchQuery === '' || 
      lesson.title.toLowerCase().includes(searchQuery.toLowerCase()) ||
      lesson.description.toLowerCase().includes(searchQuery.toLowerCase());
    
    const matchesGrade = selectedGradeLevel === 'All' || 
      lesson.gradeLevel.some(grade => grade.includes(selectedGradeLevel));
    
    const matchesSubject = selectedSubject === 'All' || lesson.subject === selectedSubject;
    
    const matchesSDG = selectedSDGGoal === 'All' || lesson.sdgGoal === selectedSDGGoal;

    return matchesSearch && matchesGrade && matchesSubject && matchesSDG;
  });

  function toggleFavorite(lessonId: number) {
    lessons = lessons.map(lesson => 
      lesson.id === lessonId 
        ? { ...lesson, isFavorited: !lesson.isFavorited }
        : lesson
    );
  }

  function applyFilters() {
    // Filters are applied reactively, so this function can be used for additional actions
    console.log('Filters applied');
  }
</script>

<div class="curriculum-library">
  <Header {currentPage} isLoggedIn={false} backgroundColor="green" {navigateTo} />

  <!-- Page Title -->
  <div class="page-title-container">
    <h1 class="page-title">Curriculum Library</h1>
  </div>

  <div class="frame-868">

    <!-- Search Section -->
    <div class="header-filters">
      <div class="rectangle-38"></div>
    </div>
    
    <div class="search_01">
      <div class="use-our-classroom-assistant-to-help-find-a-lesson">
        <span class="useourclassroomassistanttohelpfindalesson_span">
          Use our classroom assistant to help find a lesson
        </span>
      </div>
      <div class="frame-946">
        <input 
          type="text" 
          placeholder="Search or describe the type of lesson you're looking for"
          bind:value={searchQuery}
          class="search-input"
        />
        <div class="glyph">
          <div class="bounding-box"></div>
          <div class="search"></div>
        </div>
      </div>
      <div class="or-use-the-filters-below-to-refine-results">
        <span class="orusethefiltersbelowtorefineresults_span">
          or use the filters below to refine results
        </span>
      </div>
    </div>

    <!-- Main Content -->
    <div class="curriculum-library_01">
      <!-- Lessons Grid -->
      <div class="grid">
        {#each filteredLessons as lesson (lesson.id)}
          <div class="lesson-card" data-screen-size="Desktop" style="outline-color: {lesson.goalColor};">
            <div class="frame-154">
              <div class="frame-153">
                <div class="lesson-title-lorem-ipsum">
                  <span class="lessontitleloremipsum_span">{lesson.title}</span>
                </div>
                <button
                  class="icon_favorite"
                  data-state={lesson.isFavorited ? "Selected" : "Default"}
                  on:click={() => toggleFavorite(lesson.id)}
                  aria-label={lesson.isFavorited ? "Remove from favorites" : "Add to favorites"}
                >
                  <div class="ellipse-614" style="border-color: {lesson.goalColor};"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2">
                    <div class="vector_24" style="background: {lesson.goalColor};"></div>
                  </div>
                </button>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip">
                <span class="loremipsumdolorsitametconsecteturadip_span">{lesson.description}</span>
              </div>
            </div>
            <div class="frame-109">
              <div class="lesson-pill" style="background: {lesson.goalColor};">
                <div><span class="creativewriting_span">{lesson.sdgGoal}</span></div>
              </div>
              <div class="lesson-pill_01" style="background: {lesson.goalColor};">
                <div><span class="creativewriting_01_span">{lesson.subject}</span></div>
              </div>
              {#each lesson.gradeLevel as grade}
                <div class="lesson-pill_02" style="background: {lesson.goalColor};">
                  <div><span class="creativewriting_02_span">{grade}</span></div>
                </div>
              {/each}
            </div>
          </div>
        {/each}
      </div>

      <!-- Filtering Sidebar -->
      <div class="filtering">
        <div class="frame-1069">
          <div class="filter"><span class="filter_span">Filter</span></div>
          <div class="glyph_01">
            <div class="bounding-box_01"></div>
            <div class="keyboard_arrow_down"></div>
          </div>
        </div>

        <!-- Grade Level Filter -->
        <div class="grade-level">
          <div class="grade-level_01"><span class="gradelevel_01_span">Grade Level</span></div>
          <div class="grade-filter-pills">
            {#each gradeLevels as grade}
              <button 
                class="filter-pill" 
                class:selected={selectedGradeLevel === grade}
                data-state={selectedGradeLevel === grade ? "Selected" : "Default"}
                on:click={() => selectedGradeLevel = grade}
              >
                <div><span class="f-8_span">{grade}</span></div>
                {#if selectedGradeLevel === grade}
                  <div class="vector_44"></div>
                {/if}
              </button>
            {/each}
          </div>
        </div>

        <!-- Subjects Filter -->
        <div class="subjects">
          <div class="subjects_01"><span class="subjects_01_span">Subjects</span></div>
          <div class="subject-filter-pills">
            {#each subjects as subject}
              <button 
                class="filter-pill" 
                class:selected={selectedSubject === subject}
                data-state={selectedSubject === subject ? "Selected" : "Default"}
                on:click={() => selectedSubject = subject}
              >
                <div><span class="f-8_03_span">{subject}</span></div>
                {#if selectedSubject === subject}
                  <div class="vector_45"></div>
                {/if}
              </button>
            {/each}
          </div>
        </div>

        <!-- SDG Goals Filter -->
        <div class="sustainable-development-goals">
          <div class="sustainable-development-goals_01">
            <span class="sustainabledevelopmentgoals_01_span">Sustainable Development Goals</span>
          </div>
          <div class="goals-filter-pills">
            {#each sdgGoals as goal}
              <button 
                class="filter-pill_09" 
                class:selected={selectedSDGGoal === goal}
                data-state={selectedSDGGoal === goal ? "Selected" : "Default"}
                on:click={() => selectedSDGGoal = goal}
              >
                <div><span class="f-8_09_span">{goal}</span></div>
                {#if selectedSDGGoal === goal}
                  <div class="frame-1061">
                    <div class="vector_46"></div>
                  </div>
                {/if}
              </button>
            {/each}
          </div>
        </div>

        <button class="primary-button" data-size="Large" data-state="Default" on:click={applyFilters}>
          <div><span class="makeanaccount_span">Apply Filters</span></div>
        </button>
      </div>
    </div>
  </div>

  <!-- Saved Lessons Section -->
  <div class="saved-lessons">
    <div class="frame-870">
      <div class="frame-869">
        <div class="your-saved-lessons">
          <span class="yoursavedlessons_span">Your saved lessons</span>
        </div>
        <button class="secondary-button" data-size="Large" data-state="Default">
          <div><span class="makeanaccount_02_span">Go to My Account</span></div>
        </button>
      </div>
      <div class="frame-871">
        <div class="frame-969">
          {#each savedLessons as lesson (lesson.id)}
            <div class="lesson-card_20" data-screen-size="Desktop" style="outline-color: {lesson.goalColor};">
              <div class="frame-154_20">
                <div class="frame-153_20">
                  <div class="lesson-title-lorem-ipsum_20">
                    <span class="lessontitleloremipsum_20_span">{lesson.title}</span>
                  </div>
                  <div class="icon_favorite_20" data-state="Selected"></div>
                </div>
                <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_20">
                  <span class="loremipsumdolorsitametconsecteturadip_20_span">{lesson.description}</span>
                </div>
              </div>
              <div class="frame-109_20">
                <div class="lesson-pill_62" style="background: {lesson.goalColor};">
                  <div><span class="creativewriting_63_span">{lesson.sdgGoal}</span></div>
                </div>
                <div class="lesson-pill_63" style="background: {lesson.goalColor};">
                  <div><span class="creativewriting_64_span">{lesson.subject}</span></div>
                </div>
                {#each lesson.gradeLevel as grade}
                  <div class="lesson-pill_64" style="background: {lesson.goalColor};">
                    <div><span class="creativewriting_65_span">{grade}</span></div>
                  </div>
                {/each}
              </div>
            </div>
          {/each}
        </div>
        <div><span class="seemore_span">See more</span></div>
        <div class="vector-25"></div>
      </div>
    </div>
  </div>

  <Footer {navigateTo} />
</div>

<style>
  /* Custom styles for interactive elements */
  .search-input {
    width: 100%;
    height: 100%;
    border: none;
    outline: none;
    background: transparent;
    padding: 12px 25px;
    font-size: 18px;
    font-family: 'Founders Grotesk', sans-serif;
    color: #929292;
  }

  .search-input::placeholder {
    color: #929292;
  }

  .filter-pill.selected,
  .filter-pill_09.selected {
    background: var(--SFH-Green, #349552) !important;
    color: white;
  }

  .filter-pill.selected span,
  .filter-pill_09.selected span {
    color: white !important;
  }

  button {
    cursor: pointer;
    border: none;
    background: none;
  }

  .icon_favorite {
    cursor: pointer;
  }

  /* All the original CSS styles */
  :root {
    --SFH-White: white;
    --SFH-Black: black;
    --SFH-Green: #349552;
    --SFH-Cream: #FDF9F1;
    --01-No-Poverty: #E5243B;
    --02-Zero-Hunger: #DDA63A;
    --05-Gender-Equality: #FF3A21;
    --06-Clean-Water: #26BDE2;
    --07-Affordable-Clean-Energy: #F2BA44;
    --08-Decent-Work: #A21942;
  }

  .curriculum-library {
    width: 100%;
    min-height: 100vh;
    background: var(--SFH-Cream, #FDF9F1);
  }

  /* Removed duplicate header styles - now handled by Header component */

  /* Page Title */
  .page-title-container {
    padding: 120px 80px 60px;
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

  .frame-868 {
    width: 100%;
    position: relative;
    padding-bottom: 80px;
    background: var(--SFH-Cream, #FDF9F1);
  }

  .header-filters {
    width: 100%;
    height: 140px;
    position: relative;
    margin-top: 0;
    display: flex;
    justify-content: center;
    align-items: flex-start;
  }

  .rectangle-38 {
    width: calc(100% - 80px);
    max-width: 1360px;
    height: 400px;
    position: absolute;
    top: 20px;
    left: 50%;
    transform: translateX(-50%);
    border-radius: 24px;
    background: linear-gradient(180deg, rgba(52, 149, 82, 0.9) 0%, rgba(52, 149, 82, 0.6) 100%);
    box-shadow: 0 8px 32px rgba(52, 149, 82, 0.2);
  }

  .search_01 {
    width: calc(100% - 160px);
    max-width: 1000px;
    height: 240px;
    margin: 80px auto 0;
    position: relative;
    background: var(--SFH-White, white);
    overflow: hidden;
    border-radius: 24px;
    outline: none;
    box-shadow: 0 8px 40px rgba(0, 0, 0, 0.12);
    z-index: 10;
  }

  .use-our-classroom-assistant-to-help-find-a-lesson {
    width: calc(100% - 80px);
    max-width: 700px;
    height: auto;
    position: absolute;
    left: 50%;
    top: 35px;
    transform: translateX(-50%);
    text-align: center;
    padding: 0 20px;
  }

  .useourclassroomassistanttohelpfindalesson_span {
    color: var(--SFH-Green, #349552);
    font-size: 32px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 500;
    line-height: 36px;
    word-wrap: break-word;
    display: block;
  }

  .frame-946 {
    width: calc(100% - 80px);
    max-width: 700px;
    height: 56px;
    position: absolute;
    left: 50%;
    top: 135px;
    transform: translateX(-50%);
    background: var(--SFH-White, white);
    border-radius: 28px;
    outline: 2px var(--SFH-Green, #349552) solid;
    outline-offset: -2px;
    display: flex;
    align-items: center;
    box-shadow: 0 4px 16px rgba(52, 149, 82, 0.15);
  }

  .glyph {
    right: 20px;
    top: 50%;
    transform: translateY(-50%);
    position: absolute;
    overflow: hidden;
    justify-content: flex-start;
    align-items: center;
    gap: 10px;
    display: inline-flex;
  }

  .bounding-box {
    width: 20px;
    height: 20px;
    background: transparent;
  }

  .search {
    width: 15px;
    height: 15px;
    background: var(--SFH-Green, #349552);
    border-radius: 2px;
  }

  .or-use-the-filters-below-to-refine-results {
    position: absolute;
    left: 50%;
    top: 95px;
    transform: translateX(-50%);
    text-align: center;
  }

  .orusethefiltersbelowtorefineresults_span {
    color: rgba(0, 0, 0, 0.7);
    font-size: 18px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 24px;
    word-wrap: break-word;
  }

  .curriculum-library_01 {
    width: 100%;
    position: relative;
    margin-top: 80px;
    padding: 0 80px;
    overflow: hidden;
    display: flex;
    gap: 60px;
    align-items: flex-start;
    max-width: 1440px;
    margin-left: auto;
    margin-right: auto;
    background: var(--SFH-Cream, #FDF9F1);
  }

  .grid {
    flex: 1;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(340px, 1fr));
    grid-gap: 32px;
    margin-top: 0;
    padding: 0;
    justify-content: center;
  }

  .lesson-card {
    width: 100%;
    min-height: 280px;
    padding: 32px;
    background: var(--SFH-White, white);
    overflow: hidden;
    border-radius: 24px;
    outline: 2px solid;
    outline-offset: -2px;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    display: flex;
    box-sizing: border-box;
    transition: all 0.3s ease;
    position: relative;
  }

  .lesson-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 12px 40px rgba(0, 0, 0, 0.15);
  }

  .lesson-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 4px;
    border-radius: 24px 24px 0 0;
    background: inherit;
    opacity: 0.8;
  }

  .frame-154 {
    align-self: stretch;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 6px;
    display: flex;
  }

  .frame-153 {
    width: 100%;
    justify-content: space-between;
    align-items: flex-start;
    display: inline-flex;
  }

  .lesson-title-lorem-ipsum {
    flex: 1;
    margin-right: 12px;
  }

  .lessontitleloremipsum_span {
    color: var(--SFH-Black, black);
    font-size: 32px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 32px;
    word-wrap: break-word;
  }

  .icon_favorite {
    width: 36px;
    height: 36px;
    position: relative;
  }

  .ellipse-614 {
    width: 36px;
    height: 36px;
    left: 0px;
    top: 0px;
    position: absolute;
    border-radius: 9999px;
    border: 1.50px solid;
  }

  .favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2 {
    width: 16.62px;
    height: 16.62px;
    left: 9.69px;
    top: 10.64px;
    position: absolute;
    overflow: hidden;
  }

  .vector_24 {
    width: 13.85px;
    height: 12.70px;
    left: 1.38px;
    top: 1.83px;
    position: absolute;
  }

  .lorem-ipsum-dolor-sit-amet-consectetur-adip {
    align-self: stretch;
  }

  .loremipsumdolorsitametconsecteturadip_span {
    color: var(--SFH-Black, black);
    font-size: 18px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .frame-109 {
    align-self: stretch;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 6px;
    display: inline-flex;
    flex-wrap: wrap;
    align-content: flex-start;
  }

  .lesson-pill,
  .lesson-pill_01,
  .lesson-pill_02 {
    height: 28px;
    padding-bottom: 2px;
    padding-left: 12px;
    padding-right: 12px;
    overflow: hidden;
    border-radius: 53px;
    justify-content: center;
    align-items: center;
    display: flex;
  }

  .creativewriting_span,
  .creativewriting_01_span,
  .creativewriting_02_span {
    color: var(--SFH-Black, black);
    font-size: 16px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 19.20px;
    word-wrap: break-word;
  }

  .filtering {
    width: 360px;
    min-width: 360px;
    padding: 32px;
    margin-top: 0;
    background: var(--SFH-White, white);
    overflow: hidden;
    border-radius: 24px;
    outline: 2px rgba(52, 149, 82, 0.2) solid;
    outline-offset: -2px;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 32px;
    display: flex;
    flex-shrink: 0;
    align-self: flex-start;
    position: sticky;
    top: 120px;
    box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
    height: fit-content;
  }

  .frame-1069 {
    align-self: stretch;
    justify-content: space-between;
    align-items: flex-start;
    display: inline-flex;
  }

  .filter {
    width: 65.01px;
    height: 28.50px;
  }

  .filter_span {
    color: var(--SFH-Green, #349552);
    font-size: 32px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 32px;
    word-wrap: break-word;
  }

  .glyph_01 {
    transform: rotate(-180deg);
    transform-origin: top left;
    overflow: hidden;
    justify-content: flex-start;
    align-items: center;
    gap: 13.50px;
    display: flex;
  }

  .bounding-box_01 {
    width: 27px;
    height: 27px;
    background: transparent;
  }

  .keyboard_arrow_down {
    width: 16.80px;
    height: 10.06px;
    background: var(--SFH-Green, #349552);
  }

  .grade-level {
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 10px;
    display: flex;
  }

  .grade-level_01 {
    align-self: stretch;
  }

  .gradelevel_01_span {
    color: var(--SFH-Black, black);
    font-size: 18px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 500;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .grade-filter-pills {
    justify-content: flex-start;
    align-items: center;
    gap: 8px;
    display: inline-flex;
    flex-wrap: wrap;
  }

  .filter-pill {
    height: 32px;
    padding-left: 16px;
    padding-right: 16px;
    background: var(--SFH-White, white);
    overflow: hidden;
    border-radius: 16px;
    outline: 2px var(--SFH-Green, #349552) solid;
    outline-offset: -2px;
    justify-content: flex-start;
    align-items: center;
    gap: 8px;
    display: flex;
    transition: all 0.2s ease;
    cursor: pointer;
  }

  .filter-pill:hover {
    background: rgba(52, 149, 82, 0.1);
    transform: translateY(-1px);
  }

  .f-8_span,
  .f-8_03_span {
    color: var(--SFH-Black, black);
    font-size: 16px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 19.20px;
    word-wrap: break-word;
  }

  .vector_44,
  .vector_45 {
    width: 8.01px;
    height: 8.01px;
    background: var(--SFH-White, white);
  }

  .subjects {
    width: 238px;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 10px;
    display: flex;
  }

  .subjects_01 {
    align-self: stretch;
  }

  .subjects_01_span {
    color: var(--SFH-Black, black);
    font-size: 18px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 500;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .subject-filter-pills {
    width: 100%;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 8px;
    display: inline-flex;
    flex-wrap: wrap;
    align-content: flex-start;
  }

  .sustainable-development-goals {
    align-self: stretch;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 12px;
    display: flex;
  }

  .sustainable-development-goals_01 {
    width: 276px;
  }

  .sustainabledevelopmentgoals_01_span {
    color: var(--SFH-Black, black);
    font-size: 18px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 500;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .goals-filter-pills {
    align-self: stretch;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 6px;
    display: inline-flex;
    flex-wrap: wrap;
    align-content: flex-start;
  }

  .filter-pill_09 {
    height: 32px;
    padding-bottom: 0;
    padding-left: 12px;
    padding-right: 12px;
    background: var(--SFH-White, white);
    overflow: hidden;
    border-radius: 16px;
    outline: 2px var(--SFH-Green, #349552) solid;
    outline-offset: -2px;
    justify-content: flex-start;
    align-items: center;
    gap: 8px;
    display: flex;
    transition: all 0.2s ease;
    cursor: pointer;
    margin-bottom: 4px;
  }

  .filter-pill_09:hover {
    background: rgba(52, 149, 82, 0.1);
    transform: translateY(-1px);
  }

  .f-8_09_span {
    color: var(--SFH-Black, black);
    font-size: 14px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 16.80px;
    word-wrap: break-word;
  }

  .frame-1061 {
    padding-top: 2px;
    justify-content: flex-start;
    align-items: center;
    gap: 10px;
    display: flex;
  }

  .vector_46 {
    width: 8.01px;
    height: 8.01px;
    background: var(--SFH-White, white);
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

  .makeanaccount_span {
    color: var(--SFH-White, white);
    font-size: 18px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 500;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .saved-lessons {
    width: 100%;
    padding: 80px 80px;
    position: relative;
    background: var(--SFH-White, white);
    overflow: hidden;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    display: flex;
    margin-top: 100px;
  }

  .frame-870 {
    width: 100%;
    max-width: 1440px;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 50px;
    display: flex;
  }

  .frame-869 {
    align-self: stretch;
    justify-content: space-between;
    align-items: flex-start;
    display: inline-flex;
  }

  .your-saved-lessons {
    width: 417.50px;
    height: 38.50px;
  }

  .yoursavedlessons_span {
    color: var(--SFH-Black, black);
    font-size: 52px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 42px;
    word-wrap: break-word;
  }

  .secondary-button {
    height: 44px;
    padding-top: 5px;
    padding-bottom: 8px;
    padding-left: 24px;
    padding-right: 24px;
    border-radius: 40px;
    outline: 1.50px var(--SFH-Black, black) solid;
    outline-offset: -1.50px;
    justify-content: center;
    align-items: center;
    gap: 6px;
    display: flex;
  }

  .makeanaccount_02_span {
    color: var(--SFH-Black, black);
    font-size: 18px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 500;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .frame-871 {
    align-self: stretch;
    height: 249px;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    gap: 40px;
    display: flex;
  }

  .frame-969 {
    width: 100%;
    max-width: 1440px;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(340px, 1fr));
    grid-gap: 32px;
    justify-content: center;
    align-items: flex-start;
  }

  .lesson-card_20 {
    width: 100%;
    min-height: 280px;
    padding: 32px;
    background: var(--SFH-White, white);
    overflow: hidden;
    border-radius: 24px;
    outline: 2px solid;
    outline-offset: -2px;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    display: flex;
    box-sizing: border-box;
    transition: all 0.3s ease;
    position: relative;
  }

  .lesson-card_20:hover {
    transform: translateY(-4px);
    box-shadow: 0 12px 40px rgba(0, 0, 0, 0.15);
  }

  .lesson-card_20::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 4px;
    border-radius: 24px 24px 0 0;
    background: inherit;
    opacity: 0.8;
  }

  .frame-154_20 {
    align-self: stretch;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 6px;
    display: flex;
  }

  .frame-153_20 {
    width: 100%;
    justify-content: space-between;
    align-items: flex-start;
    display: inline-flex;
  }

  .lesson-title-lorem-ipsum_20 {
    flex: 1;
    margin-right: 12px;
  }

  .lessontitleloremipsum_20_span {
    color: var(--SFH-Black, black);
    font-size: 32px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 32px;
    word-wrap: break-word;
  }

  .icon_favorite_20 {
    width: 36px;
    height: 36px;
    position: relative;
  }

  .lorem-ipsum-dolor-sit-amet-consectetur-adip_20 {
    align-self: stretch;
  }

  .loremipsumdolorsitametconsecteturadip_20_span {
    color: var(--SFH-Black, black);
    font-size: 18px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 21.60px;
    word-wrap: break-word;
  }

  .frame-109_20 {
    align-self: stretch;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 6px;
    display: inline-flex;
    flex-wrap: wrap;
    align-content: flex-start;
  }

  .lesson-pill_62,
  .lesson-pill_63,
  .lesson-pill_64 {
    height: 28px;
    padding-bottom: 2px;
    padding-left: 12px;
    padding-right: 12px;
    overflow: hidden;
    border-radius: 53px;
    justify-content: center;
    align-items: center;
    display: flex;
  }

  .creativewriting_63_span,
  .creativewriting_64_span,
  .creativewriting_65_span {
    color: var(--SFH-Black, black);
    font-size: 16px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 19.20px;
    word-wrap: break-word;
  }

  .seemore_span {
    color: var(--SFH-Black, black);
    font-size: 16px;
    font-family: 'Founders Grotesk', sans-serif;
    font-weight: 400;
    line-height: 16.32px;
    word-wrap: break-word;
  }

  .vector-25 {
    width: 8.31px;
    height: 4.51px;
    outline: 1px var(--SFH-Green, #349552) solid;
    outline-offset: -0.50px;
    cursor: pointer;
    transition: all 0.2s ease;
  }

  .vector-25:hover {
    outline-color: var(--SFH-Black, black);
  }

  /* Enhanced button and interactive element styles */
  .primary-button:hover {
    background: #2d7a45;
    transform: translateY(-1px);
    box-shadow: 0 4px 16px rgba(52, 149, 82, 0.3);
  }

  .secondary-button:hover {
    background: rgba(0, 0, 0, 0.05);
    transform: translateY(-1px);
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.1);
  }

  /* Smooth transitions for all interactive elements */
  .primary-button,
  .secondary-button,
  .search-input,
  .lesson-card,
  .lesson-card_20 {
    transition: all 0.3s ease;
  }

  /* Enhanced Responsive Design */
  @media (max-width: 1440px) {
    .page-title-container {
      padding: 100px 60px 50px;
    }

    .curriculum-library_01 {
      padding: 0 60px;
      max-width: 1200px;
      gap: 50px;
    }
    
    .saved-lessons {
      padding: 80px 60px;
    }

    .filtering {
      width: 340px;
    }

    .rectangle-38 {
      width: calc(100% - 120px);
    }

    .search_01 {
      width: calc(100% - 200px);
    }
  }

  @media (max-width: 1200px) {
    .page-title-container {
      padding: 80px 40px 40px;
    }

    .curriculum-library_01 {
      gap: 40px;
      padding: 0 40px;
    }

    .grid {
      grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
      grid-gap: 28px;
    }
    
    .frame-969 {
      grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
      grid-gap: 28px;
    }

    .filtering {
      width: 320px;
    }

    .rectangle-38 {
      width: calc(100% - 80px);
    }

    .search_01 {
      width: calc(100% - 120px);
    }
  }

  @media (max-width: 968px) {
    .page-title-container {
      padding: 80px 30px 40px;
    }

    .page-title {
      font-size: 52px;
      line-height: 56px;
    }

    .curriculum-library_01 {
      flex-direction: column;
      padding: 0 30px;
      gap: 40px;
      margin-top: 60px;
    }
    
    .filtering {
      width: 100%;
      min-width: auto;
      position: relative;
      top: auto;
      margin-top: 0;
      order: -1;
      padding: 24px;
      height: auto;
    }
    
    .grid {
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      margin-top: 0;
      grid-gap: 24px;
    }

    .search_01 {
      width: calc(100% - 60px);
      margin: 60px auto 0;
      height: 220px;
    }

    .rectangle-38 {
      width: calc(100% - 60px);
      height: 380px;
    }

    .saved-lessons {
      padding: 80px 30px;
      margin-top: 100px;
    }

    .frame-969 {
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      grid-gap: 24px;
    }
  }

  @media (max-width: 768px) {
    .page-title-container {
      padding: 60px 20px 30px;
    }

    .page-title {
      font-size: 44px;
      line-height: 48px;
    }

    .curriculum-library_01 {
      padding: 0 20px;
      margin-top: 40px;
      gap: 30px;
    }
    
    .grid {
      grid-template-columns: 1fr;
      grid-gap: 20px;
    }
    
    .search_01 {
      width: calc(100% - 40px);
      margin: 60px auto 0;
      height: 200px;
    }

    .rectangle-38 {
      width: calc(100% - 40px);
      height: 360px;
    }
    
    .frame-946 {
      width: calc(100% - 60px);
      height: 50px;
      top: 120px;
    }
    
    .saved-lessons {
      padding: 60px 20px;
      margin-top: 80px;
    }
    
    .frame-969 {
      grid-template-columns: 1fr;
      grid-gap: 20px;
    }

    .use-our-classroom-assistant-to-help-find-a-lesson {
      width: calc(100% - 60px);
      top: 30px;
    }

    .useourclassroomassistanttohelpfindalesson_span {
      font-size: 28px;
      line-height: 32px;
    }

    .or-use-the-filters-below-to-refine-results {
      top: 75px;
    }

    .filtering {
      gap: 20px;
      padding: 20px;
    }

    .yoursavedlessons_span {
      font-size: 44px;
      line-height: 48px;
    }

    .frame-869 {
      flex-direction: column;
      align-items: flex-start;
      gap: 20px;
    }

    .secondary-button {
      align-self: flex-start;
    }
  }

  @media (max-width: 480px) {
    .page-title-container {
      padding: 50px 16px 25px;
    }

    .page-title {
      font-size: 36px;
      line-height: 40px;
    }

    .curriculum-library_01 {
      padding: 0 16px;
      gap: 24px;
    }

    .use-our-classroom-assistant-to-help-find-a-lesson {
      width: calc(100% - 40px);
    }

    .useourclassroomassistanttohelpfindalesson_span {
      font-size: 24px;
      line-height: 28px;
    }
    
    .frame-946 {
      width: calc(100% - 40px);
      height: 48px;
    }

    .search-input {
      font-size: 16px;
      padding: 12px 20px;
    }

    .lesson-card,
    .lesson-card_20 {
      padding: 20px;
      min-height: 260px;
    }

    .lessontitleloremipsum_span,
    .lessontitleloremipsum_20_span {
      font-size: 26px;
      line-height: 28px;
    }

    .filtering {
      padding: 16px;
      gap: 16px;
    }

    .frame-868 {
      padding-bottom: 40px;
    }

    .saved-lessons {
      padding: 50px 16px;
      margin-top: 60px;
    }

    .yoursavedlessons_span {
      font-size: 36px;
      line-height: 40px;
    }

    .search_01 {
      width: calc(100% - 32px);
      margin: 50px auto 0;
    }

    .rectangle-38 {
      width: calc(100% - 32px);
      height: 340px;
    }
  }
</style>