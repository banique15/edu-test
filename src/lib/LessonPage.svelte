<script lang="ts">
  import Header from './Header.svelte';
  import Footer from './Footer.svelte';

  export let navigateTo: (page: string) => void;
</script>

<div class="lesson-closed">
  <Header {navigateTo} />
  
  <div data-size="Desktop" class="lesson-header-desktop">
    <div class="favorite-button">
      <div data-state="Default" class="icon_favorite">
        <div class="ellipse-614"></div>
        <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2">
          <div class="vector_24"></div>
        </div>
      </div>
      <div data-size="Large" data-state="Glyph" class="secondary-button">
        <div class="glyph">
          <div class="print_24dp_000000_fill0_wght400_grad0_opsz24-1">
            <div class="vector_25"></div>
          </div>
        </div>
        <div><span class="makeanaccount_span">Print Lesson</span></div>
      </div>
    </div>
    <div class="text-left">
      <div class="top-info">
        <div class="title-pills">
          <div class="title"><span class="title_span">Unlocking the Flow</span></div>
          <div class="subhead"><span class="subhead_span">Stream of consciousness writing for a world of quality education</span></div>
        </div>
        <div class="pills">
          <div class="lesson-pill">
            <div><span class="creativewriting_span">4. Quality Education</span></div>
          </div>
          <div class="lesson-pill_01">
            <div><span class="creativewriting_01_span">Creative Writing</span></div>
          </div>
          <div class="lesson-pill_02">
            <div><span class="creativewriting_02_span">Grades 9-12</span></div>
          </div>
        </div>
        <div class="time">
          <div class="icon">
            <div class="bounding-box"></div>
            <div class="schedule"></div>
          </div>
          <div class="text-30-60-minutes"><span class="f0-60minutes_span">30-60 Minutes</span></div>
        </div>
      </div>
      <div class="materials">
        <div class="header"><span class="header_span">Materials Needed</span></div>
        <div class="frame-3-columns">
          <div class="column-1"><span class="column1_span">Paper or notebooks for writing <br/>Pens/pencils <br/>Markers</span></div>
          <div class="column-2"><span class="column2_span">Calming music or nature sounds to create a conducive writing atmosphere <br/>Whiteboard or large paper for sharing ideas</span></div>
        </div>
      </div>
    </div>
    <div data-size="Desktop" class="goal-overview">
      <div class="see-goal-7-overview"><span class="seegoal7overview_span">See Goal 4Overview</span></div>
      <div class="you-can-find-an-introduction-to-goal-7-as-well-as-the-targets-indicators-objectives-and-action-planning-resources-on-the-goal-overview-page"><span class="youcanfindanintroductiontogoal7aswellasthetargetsindicatorsobjectivesandactionplanningresourcesonthegoaloverviewpage_span">You can find an introduction to Goal 4, as well as the Targets & Indicators, Objectives, and Action Planning Resources on the Goal overview page.</span></div>
      <div class="goal-7-affordable-clean-energy"><span class="goal7affordablecleanenergy_span">Goal 4: Quality Education</span></div>
      <div class="goal-icon-circle">
        <div data-goal="4" class="goal-icon">
          <div class="frame-4">
            <div class="vector_26"></div>
            <div class="vector_27"></div>
            <div class="vector_28"></div>
            <div class="vector_29"></div>
            <div class="vector_30"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="accordians">
    <div class="frame-972">
      <div data-state="Closed" class="accordian">
        <div class="text-icon">
          <div class="text">
            <div><span class="nameofsection_span">Introduction </span></div>
            <div><span class="context_span">The Flow of Thoughts </span></div>
          </div>
          <div class="icon_01"></div>
        </div>
      </div>
      <div data-state="Closed" class="accordian_01">
        <div class="text-icon_01">
          <div class="text_01">
            <div><span class="nameofsection_01_span">Prompt Selection</span></div>
            <div><span class="context_01_span">From Targets to Thoughts </span></div>
          </div>
          <div class="icon_02"></div>
        </div>
      </div>
      <div data-state="Closed" class="accordian_02">
        <div class="text-icon_02">
          <div class="text_02">
            <div><span class="nameofsection_02_span">Free Writing</span></div>
          </div>
          <div class="icon_03"></div>
        </div>
      </div>
      <div data-state="Closed" class="accordian_03">
        <div class="text-icon_03">
          <div class="text_03">
            <div><span class="nameofsection_03_span">Sharing & Connecting</span></div>
          </div>
          <div class="icon_04"></div>
        </div>
      </div>
      <div data-state="Closed" class="accordian_04">
        <div class="text-icon_04">
          <div class="text_04">
            <div><span class="nameofsection_04_span">Reflection & Summary</span></div>
          </div>
          <div class="icon_05"></div>
        </div>
      </div>
      <div data-state="Closed" class="accordian_05">
        <div class="text-icon_05">
          <div class="text_05">
            <div><span class="nameofsection_05_span">Assessment</span></div>
          </div>
          <div class="icon_06"></div>
        </div>
      </div>
    </div>
  </div>
  <div class="bottom-of-page">
    <div class="reviewdesktop">
      <div class="frame-1045">
        <div class="frame-1044">
          <div class="lesson-reviews"><span class="lessonreviews_span">Lesson Reviews</span></div>
          <div data-size="Large" data-state="Glyph" class="secondary-button_01">
            <div class="glyph_01">
              <div class="bounding-box_01"></div>
              <div class="content_copy"></div>
            </div>
            <div><span class="makeanaccount_01_span">Share Lesson</span></div>
          </div>
        </div>
        <div class="frame-838">
          <div class="frame-837">
            <div class="frame-832">
              <div class="frame-1042">
                <div class="howd-it-go"><span class="howditgo_span">How'd it go?</span></div>
                <div class="review"><span class="review_span">Tell other educators about your experience teaching this lesson in your classroom.</span></div>
              </div>
              <div data-size="Large" data-state="Glyph" class="secondary-button_02">
                <div><span class="makeanaccount_02_span">Leave a review</span></div>
              </div>
            </div>
            <div class="frame-836">
              <div class="review_01">
                <div class="name-stars">
                  <div class="name-image-pills">
                    <div class="name-image-pills_01">
                      <img class="image" src="https://placehold.co/32x32" />
                      <div class="name">
                        <div><span class="name_01_span">Amanda H.</span></div>
                        <div><span class="city_span">Minneapolis, MN, USA</span></div>
                        <div data-size="Regular" data-state="Default" class="filter-pill">
                          <div><span class="f-8_span">Music</span></div>
                        </div>
                        <div data-size="Regular" data-state="Default" class="filter-pill_01">
                          <div><span class="f-8_01_span">Dance & Movement</span></div>
                        </div>
                      </div>
                    </div>
                    <div class="stars">
                      <div class="icon_07">
                        <div class="bounding-box_02"></div>
                        <div class="star"></div>
                      </div>
                      <div class="icon_08">
                        <div class="bounding-box_03"></div>
                        <div class="star_01"></div>
                      </div>
                      <div class="icon_09">
                        <div class="bounding-box_04"></div>
                        <div class="star_02"></div>
                      </div>
                      <div class="icon_10">
                        <div class="bounding-box_05"></div>
                        <div class="star_03"></div>
                      </div>
                      <div class="icon_11">
                        <div class="bounding-box_06"></div>
                        <div class="star_04"></div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="copy">
                  <div class="review_02"><span class="review_02_span">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc tincidunt eros eget venenatis hendrerit. Donec quis nunc quis ipsum dapibus facilisis. Morbi dolor orci, convallis non egestas non, bibendum at purus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc tincidunt eros eget venenatis hendrerit. Donec quis nunc quis ipsum dapibus facilisis. Morbi dolor orci, convallis non egestas non, bibendum at purus.Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc tincidunt eros eget venenatis hendrerit. Donec quis nunc quis ipsum dapibus facilisis. Morbi dolor orci, convallis non egestas non, bibendum at purus.</span></div>
                  <div class="frame-1043">
                    <div class="content">
                      <div class="october-23-2025"><span class="october232025_span">October 23, 2025</span></div>
                    </div>
                    <div class="read-more"><span class="readmore_span">Read More</span></div>
                  </div>
                </div>
              </div>
              <div class="user-review">
                <div class="name-and-star-container">
                  <div class="name-and-badge">
                    <img class="avatar" src="https://placehold.co/32x32" />
                    <div class="frame-817">
                      <div><span class="amyrobson_span">John F.</span></div>
                      <div><span class="fmonthago_span">Los Angeles, CA, USA</span></div>
                      <div data-size="Regular" data-state="Default" class="filter-pill_02">
                        <div><span class="f-8_02_span">Music</span></div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="content_01">
                  <div class="lorem-ipsum-dolor-sit-amet-consectetur-adipiscing-elit"><span class="loremipsumdolorsitametconsecteturadipiscingelit_span">Lorem ipsum dolor sit amet, consectetur adipiscing elit. </span></div>
                </div>
                <div class="content_02">
                  <div class="october-23-2025_01"><span class="october232025_01_span">October 23, 2025</span></div>
                </div>
              </div>
            </div>
          </div>
          <div class="line-8"></div>
          <div class="review_03">
            <div class="name-stars_01">
              <div class="name-image-pills_02">
                <div class="name-image-pills_03">
                  <img class="image_01" src="https://placehold.co/32x32" />
                  <div class="name_02">
                    <div><span class="name_03_span">Jeremy S.</span></div>
                    <div><span class="city_01_span">Minneapolis, MN, USA</span></div>
                    <div data-size="Regular" data-state="Default" class="filter-pill_03">
                      <div><span class="f-8_03_span">Dance & Movement</span></div>
                    </div>
                  </div>
                </div>
                <div class="stars_01">
                  <div class="icon_12">
                    <div class="bounding-box_07"></div>
                    <div class="star_05"></div>
                  </div>
                  <div class="icon_13">
                    <div class="bounding-box_08"></div>
                    <div class="star_06"></div>
                  </div>
                  <div class="icon_14">
                    <div class="bounding-box_09"></div>
                    <div class="star_07"></div>
                  </div>
                  <div class="icon_15">
                    <div class="bounding-box_10"></div>
                    <div class="star_08"></div>
                  </div>
                  <div class="icon_16">
                    <div class="bounding-box_11"></div>
                    <div class="star_09"></div>
                  </div>
                </div>
              </div>
            </div>
            <div class="copy_01">
              <div class="review_04"><span class="review_04_span">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc tincidunt eros eget venenatis hendrerit. Donec quis nunc quis ipsum dapibus facilisis. Morbi dolor orci, convallis non egestas non, bibendum at purus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc tincidunt eros eget venenatis hendrerit. Donec quis nunc quis ipsum dapibus facilisis. `</span></div>
            </div>
            <div class="frame-1043_01">
              <div class="content_03">
                <div class="september-30-2025"><span class="september302025_span">September 30, 2025</span></div>
              </div>
              <div class="read-more_01"><span class="readmore_01_span">Read More</span></div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="featured-lessons">
      <div class="header-button-cards">
        <div class="header-button">
          <div class="more-creative-writing-lessons"><span class="morecreativewritinglessons_span">More Creative Writing Lessons</span></div>
          <div data-size="Large" data-state="Default" class="secondary-button_03">
            <div><span class="makeanaccount_03_span">See All</span></div>
          </div>
        </div>
        <div class="cards">
          <div data-screen-size="Desktop" class="lesson-card">
            <div class="frame-154">
              <div class="frame-153">
                <div class="lesson-title-lorem-ipsum"><span class="lessontitleloremipsum_span">Words That Flow</span></div>
                <div data-state="Default" class="icon_favorite_01">
                  <div class="ellipse-614_01"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_01">
                    <div class="vector_31"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip"><span class="loremipsumdolorsitametconsecteturadip_span">Painting with words for clean water painting with words for clean water </span></div>
            </div>
            <div class="frame-109">
              <div class="lesson-pill_03">
                <div><span class="creativewriting_03_span">6. Clean Water & Sanitation</span></div>
              </div>
              <div class="lesson-pill_04">
                <div><span class="creativewriting_04_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_05">
                <div><span class="creativewriting_05_span">Grades 9-12</span></div>
              </div>
            </div>
          </div>
          <div data-screen-size="Desktop" class="lesson-card_01">
            <div class="frame-154_01">
              <div class="frame-153_01">
                <div class="lesson-title-lorem-ipsum_01"><span class="lessontitleloremipsum_01_span">The Power of Words</span></div>
                <div data-state="Default" class="icon_favorite_02">
                  <div class="ellipse-614_02"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_02">
                    <div class="vector_32"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_01"><span class="loremipsumdolorsitametconsecteturadip_01_span">Convincing for clean energy</span></div>
            </div>
            <div class="frame-109_01">
              <div class="lesson-pill_06">
                <div><span class="creativewriting_06_span">7. Affordable Clean Energy</span></div>
              </div>
              <div class="lesson-pill_07">
                <div><span class="creativewriting_07_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_08">
                <div><span class="creativewriting_08_span">Grades 9-12</span></div>
              </div>
            </div>
          </div>
          <div data-screen-size="Desktop" class="lesson-card_02">
            <div class="frame-154_02">
              <div class="frame-153_02">
                <div class="lesson-title-lorem-ipsum_02"><span class="lessontitleloremipsum_02_span">Haiku for Humanity</span></div>
                <div data-state="Default" class="icon_favorite_03">
                  <div class="ellipse-614_03"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_03">
                    <div class="vector_33"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_02"><span class="loremipsumdolorsitametconsecteturadip_02_span">Tiny words for big work</span></div>
            </div>
            <div class="frame-109_02">
              <div class="lesson-pill_09">
                <div><span class="creativewriting_09_span">8. Decent Work & Economic Growth</span></div>
              </div>
              <div class="lesson-pill_10">
                <div><span class="creativewriting_10_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_11">
                <div><span class="creativewriting_11_span">Grades 9-12</span></div>
              </div>
            </div>
          </div>
          <div data-screen-size="Desktop" class="lesson-card_03">
            <div class="frame-154_03">
              <div class="frame-153_03">
                <div class="lesson-title-lorem-ipsum_03"><span class="lessontitleloremipsum_03_span">Words That Spark Change</span></div>
                <div data-state="Default" class="icon_favorite_04">
                  <div class="ellipse-614_04"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_04">
                    <div class="vector_34"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_03"><span class="loremipsumdolorsitametconsecteturadip_03_span">Writing for fairness and equality</span></div>
            </div>
            <div class="frame-109_03">
              <div class="lesson-pill_12">
                <div><span class="creativewriting_12_span">5. Gender Equality</span></div>
              </div>
              <div class="lesson-pill_13">
                <div><span class="creativewriting_13_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_14">
                <div><span class="creativewriting_14_span">Grades 9-12</span></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  
  <Footer {navigateTo} />
</div>

<style>
.vector {
  width: 9.90px;
  height: 11.92px;
  left: 88.96px;
  top: 9.26px;
  position: absolute;
}

.vector_01 {
  width: 9.90px;
  height: 11.92px;
  left: 105.97px;
  top: 9.26px;
  position: absolute;
}

.vector_02 {
  width: 7.57px;
  height: 6px;
  left: 31.86px;
  top: 15.28px;
  position: absolute;
}

.vector_03 {
  width: 21.54px;
  height: 23.49px;
  left: 0px;
  top: -0.01px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_04 {
  width: 2.97px;
  height: 22.60px;
  left: 23.71px;
  top: 0.43px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_05 {
  width: 16.01px;
  height: 16.54px;
  left: 28.89px;
  top: 6.92px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_06 {
  width: 13.59px;
  height: 16.55px;
  left: 45.50px;
  top: 6.91px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_07 {
  width: 13.59px;
  height: 16.55px;
  left: 60.53px;
  top: 6.91px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_08 {
  width: 9.65px;
  height: 16.12px;
  left: 76.48px;
  top: 6.93px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_09 {
  width: 16px;
  height: 16.55px;
  left: 85.92px;
  top: 6.93px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_10 {
  width: 16px;
  height: 16.55px;
  left: 102.93px;
  top: 6.93px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_11 {
  width: 23.90px;
  height: 16.12px;
  left: 120.94px;
  top: 6.93px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_12 {
  width: 10.42px;
  height: 16.57px;
  left: 14.95px;
  top: 41.77px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_13 {
  width: 12.48px;
  height: 12.56px;
  left: 28.16px;
  top: 46.08px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_14 {
  width: 12.45px;
  height: 16.63px;
  left: 43.78px;
  top: 46.07px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_15 {
  width: 12.33px;
  height: 12.56px;
  left: 58.50px;
  top: 46.07px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_16 {
  width: 3.33px;
  height: 9.74px;
  left: 48.86px;
  top: 34.56px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_17 {
  width: 7.20px;
  height: 7.24px;
  left: 52.75px;
  top: 37.22px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_18 {
  width: 3.48px;
  height: 7.07px;
  left: 60.99px;
  top: 37.22px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_19 {
  width: 5.54px;
  height: 9.74px;
  left: 17.55px;
  top: 27.41px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_20 {
  width: 1.96px;
  height: 13.07px;
  left: 24.54px;
  top: 23.84px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_21 {
  width: 8.08px;
  height: 9.49px;
  left: 28.50px;
  top: 27.41px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_22 {
  width: 9.65px;
  height: 13.12px;
  left: 37.87px;
  top: 27.41px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_23 {
  width: 85.13px;
  height: 85.87px;
  left: 0px;
  top: 0px;
  position: absolute;
  background: var(--SFH-Green, #349552);
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
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.about_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.ellipse-614 {
  width: 44px;
  height: 44px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.83px var(--SFH-White, white) solid;
}

.vector_24 {
  width: 16.92px;
  height: 15.53px;
  left: 1.69px;
  top: 2.24px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_25 {
  width: 16.67px;
  height: 15px;
  left: 1.67px;
  top: 2.50px;
  position: absolute;
  background: var(--SFH-White, white);
}

.makeanaccount_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 21.60px;
  word-wrap: break-word;
}

.title_span {
  color: var(--SFH-White, white);
  font-size: 60px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 54px;
  word-wrap: break-word;
}

.title {
  align-self: stretch;
  height: 54px;
}

.subhead_span {
  color: var(--SFH-White, white);
  font-size: 24px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 31.20px;
  word-wrap: break-word;
}

.subhead {
  width: 604.79px;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.creativewriting_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_01_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_02_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.bounding-box {
  width: 24.20px;
  height: 24.20px;
  background: #D9D9D9;
}

.schedule {
  width: 20.16px;
  height: 20.16px;
  background: var(--SFH-White, white);
}

.f0-60minutes_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.text-30-60-minutes {
  width: 220.94px;
}

.header_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 21.60px;
  word-wrap: break-word;
}

.header {
  align-self: stretch;
}

.column1_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.column-1 {
  width: 243.33px;
}

.column2_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.column-2 {
  width: 243.33px;
}

.seegoal7overview_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  text-decoration: underline;
  line-height: 19.20px;
  word-wrap: break-word;
}

.see-goal-7-overview {
  width: 299px;
  height: 18px;
  left: 26.50px;
  top: 162.69px;
  position: absolute;
}

.youcanfindanintroductiontogoal7aswellasthetargetsindicatorsobjectivesandactionplanningresourcesonthegoaloverviewpage_span {
  color: rgba(0, 0, 0, 0.60);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.you-can-find-an-introduction-to-goal-7-as-well-as-the-targets-indicators-objectives-and-action-planning-resources-on-the-goal-overview-page {
  width: 299px;
  height: 56px;
  left: 26.50px;
  top: 95.72px;
  position: absolute;
}

.goal7affordablecleanenergy_span {
  color: var(--SFH-Black, black);
  font-size: 28px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 28px;
  word-wrap: break-word;
}

.goal-7-affordable-clean-energy {
  width: 231px;
  left: 26.50px;
  top: 22.76px;
  position: absolute;
}

.vector_26 {
  width: 12.58px;
  height: 27.29px;
  background: var(--SFH-White, white);
}

.vector_27 {
  width: 12.66px;
  height: 27.30px;
  background: var(--SFH-White, white);
}

.vector_28 {
  width: 2.97px;
  height: 26.11px;
  background: var(--SFH-White, white);
}

.vector_29 {
  width: 32.01px;
  height: 29.97px;
  background: var(--SFH-White, white);
}

.vector_30 {
  width: 2.98px;
  height: 3.09px;
  background: white;
}

.nameofsection_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 32px;
  word-wrap: break-word;
}

.context_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.icon_01 {
  width: 23.50px;
  height: 11.75px;
  outline: 3px var(--SFH-Black, black) solid;
  outline-offset: -1.50px;
}

.nameofsection_01_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 32px;
  word-wrap: break-word;
}

.context_01_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.icon_02 {
  width: 23.50px;
  height: 11.75px;
  outline: 3px var(--SFH-Black, black) solid;
  outline-offset: -1.50px;
}

.nameofsection_02_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 32px;
  word-wrap: break-word;
}

.icon_03 {
  width: 23.50px;
  height: 11.75px;
  outline: 3px var(--SFH-Black, black) solid;
  outline-offset: -1.50px;
}

.nameofsection_03_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 32px;
  word-wrap: break-word;
}

.icon_04 {
  width: 23.50px;
  height: 11.75px;
  outline: 3px var(--SFH-Black, black) solid;
  outline-offset: -1.50px;
}

.nameofsection_04_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 32px;
  word-wrap: break-word;
}

.icon_05 {
  width: 23.50px;
  height: 11.75px;
  outline: 3px var(--SFH-Black, black) solid;
  outline-offset: -1.50px;
}

.nameofsection_05_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 32px;
  word-wrap: break-word;
}

.icon_06 {
  width: 23.50px;
  height: 11.75px;
  outline: 3px var(--SFH-Black, black) solid;
  outline-offset: -1.50px;
}

.lessonreviews_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-reviews {
  width: 673px;
  height: 30px;
}

.bounding-box_01 {
  width: 20px;
  height: 20px;
  left: -0.40px;
  top: 0.14px;
  position: absolute;
  background: #D9D9D9;
}

.content_copy {
  width: 14.17px;
  height: 16.67px;
  left: 2.10px;
  top: 1.81px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.makeanaccount_01_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 21.60px;
  word-wrap: break-word;
}

.howditgo_span {
  color: var(--SFH-White, white);
  font-size: 28px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 28px;
  word-wrap: break-word;
}

.howd-it-go {
  align-self: stretch;
}

.review_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.review {
  width: 598.20px;
}

.makeanaccount_02_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 21.60px;
  word-wrap: break-word;
}

.image {
  width: 32px;
  height: 32px;
  background: var(--SFH-Black, black);
  border-radius: 9999px;
}

.name_01_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 21.60px;
  word-wrap: break-word;
}

.city_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.f-8_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.f-8_01_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.bounding-box_02 {
  width: 32px;
  height: 32px;
  background: #D9D9D9;
}

.star {
  width: 23.44px;
  height: 22.39px;
  background: var(--SFH-Green, #349552);
}

.bounding-box_03 {
  width: 32px;
  height: 32px;
  background: #D9D9D9;
}

.star_01 {
  width: 23.44px;
  height: 22.39px;
  background: var(--SFH-Green, #349552);
}

.bounding-box_04 {
  width: 32px;
  height: 32px;
  background: #D9D9D9;
}

.star_02 {
  width: 23.44px;
  height: 22.39px;
  background: var(--SFH-Green, #349552);
}

.bounding-box_05 {
  width: 32px;
  height: 32px;
  background: #D9D9D9;
}

.star_03 {
  width: 23.44px;
  height: 22.39px;
  background: var(--SFH-Green, #349552);
}

.bounding-box_06 {
  width: 32px;
  height: 32px;
  background: #D9D9D9;
}

.star_04 {
  width: 23.44px;
  height: 22.39px;
  background: var(--SFH-Green, #349552);
}

.review_02_span {
  color: rgba(0, 0, 0, 0.60);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 27px;
  word-wrap: break-word;
}

.review_02 {
  align-self: stretch;
  height: 86.71px;
}

.october232025_span {
  color: rgba(0, 0, 0, 0.60);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.october-23-2025 {
  width: 408px;
  height: 16.67px;
}

.readmore_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 19.20px;
  word-wrap: break-word;
}

.read-more {
  text-align: right;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.avatar {
  width: 32px;
  height: 32px;
  background: var(--SFH-Black, black);
  border-radius: 9999px;
}

.amyrobson_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 21.60px;
  word-wrap: break-word;
}

.fmonthago_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.f-8_02_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.loremipsumdolorsitametconsecteturadipiscingelit_span {
  color: rgba(0, 0, 0, 0.60);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adipiscing-elit {
  width: 408px;
  height: 27px;
}

.october232025_01_span {
  color: rgba(0, 0, 0, 0.60);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.october-23-2025_01 {
  width: 408px;
  height: 16.67px;
}

.line-8 {
  align-self: stretch;
  height: 0px;
  outline: 1px rgba(0, 0, 0, 0.50) solid;
  outline-offset: -0.50px;
}

.image_01 {
  width: 32px;
  height: 32px;
  background: var(--SFH-Black, black);
  border-radius: 9999px;
}

.name_03_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 21.60px;
  word-wrap: break-word;
}

.city_01_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.f-8_03_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.bounding-box_07 {
  width: 32px;
  height: 32px;
  background: #D9D9D9;
}

.star_05 {
  width: 23.44px;
  height: 22.39px;
  background: var(--SFH-Green, #349552);
}

.bounding-box_08 {
  width: 32px;
  height: 32px;
  background: #D9D9D9;
}

.star_06 {
  width: 23.44px;
  height: 22.39px;
  background: var(--SFH-Green, #349552);
}

.bounding-box_09 {
  width: 32px;
  height: 32px;
  background: #D9D9D9;
}

.star_07 {
  width: 23.44px;
  height: 22.39px;
  background: var(--SFH-Green, #349552);
}

.bounding-box_10 {
  width: 32px;
  height: 32px;
  background: #D9D9D9;
}

.star_08 {
  width: 23.44px;
  height: 22.39px;
  background: var(--SFH-Green, #349552);
}

.bounding-box_11 {
  width: 32px;
  height: 32px;
  background: #D9D9D9;
}

.star_09 {
  width: 23.44px;
  height: 22.39px;
  background: var(--SFH-Green, #349552);
}

.review_04_span {
  color: rgba(0, 0, 0, 0.60);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 27px;
  word-wrap: break-word;
}

.review_04 {
  align-self: stretch;
  height: 86.71px;
}

.september302025_span {
  color: rgba(0, 0, 0, 0.60);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.september-30-2025 {
  width: 408px;
  height: 16.67px;
}

.readmore_01_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 19.20px;
  word-wrap: break-word;
}

.read-more_01 {
  text-align: right;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.morecreativewritinglessons_span {
  color: var(--SFH-Black, black);
  font-size: 52px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 42px;
  word-wrap: break-word;
}

.more-creative-writing-lessons {
  width: 682px;
  height: 38.50px;
}

.makeanaccount_03_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lessontitleloremipsum_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum {
  width: 217px;
}

.ellipse-614_01 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--06_Clean-Water, #26BDE2) solid;
}

.vector_31 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--06_Clean-Water, #26BDE2);
}

.loremipsumdolorsitametconsecteturadip_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip {
  align-self: stretch;
}

.creativewriting_03_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_04_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_05_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_01_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_01 {
  width: 217px;
}

.ellipse-614_02 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px #F2BA44 solid;
}

.vector_32 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: #F2BA44;
}

.loremipsumdolorsitametconsecteturadip_01_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_01 {
  align-self: stretch;
}

.creativewriting_06_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_07_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_08_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_02_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_02 {
  width: 217px;
}

.ellipse-614_03 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--08_Decent-Work, #A21942) solid;
}

.vector_33 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--08_Decent-Work, #A21942);
}

.loremipsumdolorsitametconsecteturadip_02_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_02 {
  align-self: stretch;
}

.creativewriting_09_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_10_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_11_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_03_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_03 {
  width: 217px;
}

.ellipse-614_04 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--05_Gender-Equality, #FF3A21) solid;
}

.vector_34 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--05_Gender-Equality, #FF3A21);
}

.loremipsumdolorsitametconsecteturadip_03_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_03 {
  align-self: stretch;
}

.creativewriting_12_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_13_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_14_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.curriculum_01_span {
  color: var(--SFH-White, white);
  font-size: 30.68px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 36.75px;
  word-wrap: break-word;
}

.curriculum_01 {
  width: 194.85px;
  left: 78px;
  top: 77.76px;
  position: absolute;
}

.about_01_span {
  color: var(--SFH-White, white);
  font-size: 24px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 28.75px;
  word-wrap: break-word;
}

.about_01 {
  width: 194.85px;
  left: 293.14px;
  top: 258.76px;
  position: absolute;
}

.contributors_span {
  color: var(--SFH-White, white);
  font-size: 24px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 28.75px;
  word-wrap: break-word;
}

.contributors {
  width: 194.85px;
  left: 295px;
  top: 296.26px;
  position: absolute;
}

.bysubject_span {
  color: var(--SFH-White, white);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 24px;
  word-wrap: break-word;
}

.by-subject {
  width: 114.31px;
  left: 78px;
  top: 136.76px;
  position: absolute;
}

.bygrade_span {
  color: var(--SFH-White, white);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 24px;
  word-wrap: break-word;
}

.by-grade {
  width: 114.31px;
  left: 78px;
  top: 313.26px;
  position: absolute;
}

.byglobalgoal_span {
  color: var(--SFH-White, white);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 24px;
  word-wrap: break-word;
}

.by-global-goal {
  width: 133px;
  left: 295px;
  top: 136.76px;
  position: absolute;
}

.visualart_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.visual-art {
  align-self: stretch;
}

.creativewriting_15_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.creative-writing_15 {
  align-self: stretch;
}

.dancemovement_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.dance-movement {
  align-self: stretch;
}

.music_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.music {
  align-self: stretch;
}

.drama_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.drama {
  align-self: stretch;
}

.copyright2025singforhopeincallrightsreserved_span {
  color: rgba(255, 255, 255, 0.50);
  font-size: 14px;
  font-family: Proxima Nova;
  font-weight: 400;
  line-height: 16.77px;
  word-wrap: break-word;
}

.copyright-2025-sing-for-hope-inc-all-rights-reserved {
  width: 509.43px;
  left: 78px;
  top: 452.42px;
  position: absolute;
}

.grades5-8_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.grades-5-8 {
  align-self: stretch;
}

.grades9-12_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.grades-9-12 {
  align-self: stretch;
}

.singforhope_span {
  color: var(--SFH-Black, black);
  font-size: 28px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 28px;
  word-wrap: break-word;
}

.sing-for-hope {
  align-self: stretch;
}

.ourcreativeprogramsbringhopehealingandconnectiontomillionsofpeopleinhospitalscarefacilitiesschoolsrefugeecampstransithubsandcommunityspacesworldwide_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.our-creative-programs-bring-hope-healing-and-connection-to-millions-of-people-in-hospitals-care-facilities-schools-refugee-camps-transit-hubs-and-community-spaces-worldwide {
  width: 385px;
  height: 110px;
}

.makeanaccount_04_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 21.60px;
  word-wrap: break-word;
}

.vector_35 {
  width: 15.30px;
  height: 24.32px;
  left: 21.95px;
  top: 61.33px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_36 {
  width: 18.32px;
  height: 18.45px;
  left: 41.34px;
  top: 67.65px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_37 {
  width: 18.28px;
  height: 24.42px;
  left: 64.27px;
  top: 67.64px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_38 {
  width: 18.11px;
  height: 18.45px;
  left: 85.90px;
  top: 67.64px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.vector_39 {
  width: 4.89px;
  height: 14.30px;
  left: 71.73px;
  top: 50.75px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_40 {
  width: 10.57px;
  height: 10.63px;
  left: 77.45px;
  top: 54.64px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_41 {
  width: 5.11px;
  height: 10.38px;
  left: 89.55px;
  top: 54.65px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_42 {
  width: 8.13px;
  height: 14.30px;
  left: 25.78px;
  top: 40.25px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_43 {
  width: 2.87px;
  height: 19.19px;
  left: 36.04px;
  top: 35px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_44 {
  width: 11.86px;
  height: 13.94px;
  left: 41.84px;
  top: 40.25px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_45 {
  width: 14.17px;
  height: 19.26px;
  left: 55.61px;
  top: 40.25px;
  position: absolute;
  background: var(--SFH-Black, black);
}

.vector_46 {
  width: 124.99px;
  height: 126.08px;
  left: 0px;
  top: 0px;
  position: absolute;
  background: var(--SFH-Green, #349552);
}

.selectagoal_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
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

.vector_47 {
  width: 120.86px;
  height: 72.06px;
  left: 1083.84px;
  top: 371.26px;
  position: absolute;
  background: white;
}

.vector_48 {
  width: 20.93px;
  height: 26.55px;
  left: 1088.72px;
  top: 409.83px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_49 {
  width: 24.03px;
  height: 25.83px;
  left: 1136.62px;
  top: 410.20px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_50 {
  width: 16.50px;
  height: 25.83px;
  left: 1162.26px;
  top: 410.20px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_51 {
  width: 19.67px;
  height: 26.54px;
  left: 1179.91px;
  top: 409.86px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_52 {
  width: 6.19px;
  height: 5.68px;
  left: 1114.03px;
  top: 414.01px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_53 {
  width: 5.39px;
  height: 6.29px;
  left: 1128.34px;
  top: 411.45px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_54 {
  width: 6.10px;
  height: 4.32px;
  left: 1132.01px;
  top: 418px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_55 {
  width: 6.15px;
  height: 5.68px;
  left: 1130.53px;
  top: 414.12px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_56 {
  width: 5.79px;
  height: 3.99px;
  left: 1112.44px;
  top: 422.55px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_57 {
  width: 5.85px;
  height: 6.12px;
  left: 1129.58px;
  top: 428.03px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_58 {
  width: 5.79px;
  height: 3.92px;
  left: 1132.43px;
  top: 422.59px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_59 {
  width: 5.88px;
  height: 6.10px;
  left: 1115.32px;
  top: 428.14px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_60 {
  width: 6.14px;
  height: 4.34px;
  left: 1112.55px;
  top: 417.90px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_61 {
  width: 4.68px;
  height: 6.28px;
  left: 1127.17px;
  top: 429.77px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_62 {
  width: 6.19px;
  height: 5.04px;
  left: 1131.42px;
  top: 425.74px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_63 {
  width: 3.97px;
  height: 5.74px;
  left: 1123.43px;
  top: 430.63px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_64 {
  width: 3.82px;
  height: 6.02px;
  left: 1125.79px;
  top: 410.42px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_65 {
  width: 4.74px;
  height: 6.25px;
  left: 1118.94px;
  top: 429.84px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_66 {
  width: 3.87px;
  height: 6px;
  left: 1121.11px;
  top: 410.41px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_67 {
  width: 6.26px;
  height: 5.16px;
  left: 1113.05px;
  top: 425.76px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_68 {
  width: 5.35px;
  height: 6.24px;
  left: 1117.04px;
  top: 411.42px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_69 {
  width: 9.22px;
  height: 12.13px;
  left: 1089.05px;
  top: 378.20px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_70 {
  width: 9.21px;
  height: 11.96px;
  left: 1099.84px;
  top: 378.35px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_71 {
  width: 9.22px;
  height: 12.13px;
  left: 1110.61px;
  top: 378.20px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_72 {
  width: 9.78px;
  height: 11.79px;
  left: 1120.85px;
  top: 378.37px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_73 {
  width: 11.27px;
  height: 11.79px;
  left: 1130.11px;
  top: 378.37px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_74 {
  width: 2.81px;
  height: 11.79px;
  left: 1142.58px;
  top: 378.37px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_75 {
  width: 9.78px;
  height: 11.79px;
  left: 1147.52px;
  top: 378.37px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_76 {
  width: 11.27px;
  height: 11.79px;
  left: 1158.48px;
  top: 378.37px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_77 {
  width: 9.07px;
  height: 11.79px;
  left: 1170.77px;
  top: 378.37px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_78 {
  width: 7.73px;
  height: 11.79px;
  left: 1181.55px;
  top: 378.37px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_79 {
  width: 8.08px;
  height: 11.79px;
  left: 1190.63px;
  top: 378.37px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_80 {
  width: 9px;
  height: 11.56px;
  left: 1089.39px;
  top: 394.55px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_81 {
  width: 7.62px;
  height: 11.56px;
  left: 1099.50px;
  top: 394.55px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_82 {
  width: 10.71px;
  height: 11.56px;
  left: 1107.83px;
  top: 394.55px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_83 {
  width: 7.59px;
  height: 11.56px;
  left: 1119.37px;
  top: 394.55px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_84 {
  width: 7.14px;
  height: 11.56px;
  left: 1127.89px;
  top: 394.55px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_85 {
  width: 10.04px;
  height: 11.88px;
  left: 1135.29px;
  top: 394.39px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_86 {
  width: 9.02px;
  height: 11.56px;
  left: 1146.41px;
  top: 394.55px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_87 {
  width: 12.38px;
  height: 11.56px;
  left: 1156.45px;
  top: 394.55px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_88 {
  width: 7.64px;
  height: 11.56px;
  left: 1170.06px;
  top: 394.55px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_89 {
  width: 9.58px;
  height: 11.56px;
  left: 1178.62px;
  top: 394.55px;
  position: absolute;
  background: var(--SFH-White, white);
}

.vector_90 {
  width: 9.59px;
  height: 11.56px;
  left: 1189.12px;
  top: 394.55px;
  position: absolute;
  background: var(--SFH-White, white);
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
  left: 1231.93px;
  top: 377.17px;
  position: absolute;
  background: var(--SFH-White, white);
}

.frame-30 {
  left: 542px;
  top: 48.61px;
  position: absolute;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 59px;
  display: inline-flex;
}

.title-pills {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 20px;
  display: flex;
}

.lesson-pill {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--04_Quality-Education_Tint, #850010);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_01 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--04_Quality-Education_Tint, #850010);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_02 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--04_Quality-Education_Tint, #850010);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.frame-3-columns {
  align-self: stretch;
  height: 107px;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 20px;
  display: inline-flex;
}

.text {
  justify-content: flex-start;
  align-items: center;
  gap: 12px;
  display: flex;
}

.text_01 {
  justify-content: flex-start;
  align-items: center;
  gap: 12px;
  display: flex;
}

.text_02 {
  justify-content: flex-start;
  align-items: center;
  gap: 12px;
  display: flex;
}

.text_03 {
  justify-content: flex-start;
  align-items: center;
  gap: 12px;
  display: flex;
}

.text_04 {
  justify-content: flex-start;
  align-items: center;
  gap: 12px;
  display: flex;
}

.text_05 {
  justify-content: flex-start;
  align-items: center;
  gap: 12px;
  display: flex;
}

.frame-1042 {
  width: 598px;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  gap: 10px;
  display: inline-flex;
}

.secondary-button_02 {
  height: 44px;
  padding-top: 5px;
  padding-bottom: 8px;
  padding-left: 24px;
  padding-right: 24px;
  border-radius: 40px;
  outline: 1.50px var(--SFH-White, white) solid;
  outline-offset: -1.50px;
  justify-content: center;
  align-items: center;
  gap: 6px;
  display: flex;
}

.filter-pill {
  height: 28px;
  padding-left: 14px;
  padding-right: 14px;
  overflow: hidden;
  border-radius: 49.92px;
  outline: 1.50px var(--SFH-Black, black) solid;
  outline-offset: -1.50px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.filter-pill_01 {
  height: 28px;
  padding-left: 14px;
  padding-right: 14px;
  overflow: hidden;
  border-radius: 49.92px;
  outline: 1.50px var(--SFH-Black, black) solid;
  outline-offset: -1.50px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.content {
  width: 488px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 16px;
  display: inline-flex;
}

.filter-pill_02 {
  height: 28px;
  padding-left: 14px;
  padding-right: 14px;
  overflow: hidden;
  border-radius: 49.92px;
  outline: 1.50px var(--SFH-Black, black) solid;
  outline-offset: -1.50px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.content_01 {
  width: 488px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 16px;
  display: flex;
}

.content_02 {
  width: 488px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 16px;
  display: flex;
}

.filter-pill_03 {
  height: 28px;
  padding-left: 14px;
  padding-right: 14px;
  overflow: hidden;
  border-radius: 49.92px;
  outline: 1.50px var(--SFH-Black, black) solid;
  outline-offset: -1.50px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.copy_01 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 16px;
  display: flex;
}

.content_03 {
  width: 488px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 16px;
  display: inline-flex;
}

.secondary-button_03 {
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

.lesson-pill_03 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--06_Clean-Water, #26BDE2);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_04 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--06_Clean-Water, #26BDE2);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_05 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--06_Clean-Water, #26BDE2);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_06 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: #F2BA44;
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_07 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: #F2BA44;
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_08 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: #F2BA44;
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_09 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--08_Decent-Work, #A21942);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_10 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--08_Decent-Work, #A21942);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_11 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--08_Decent-Work, #A21942);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_12 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--05_Gender-Equality, #FF3A21);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_13 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--05_Gender-Equality, #FF3A21);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_14 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--05_Gender-Equality, #FF3A21);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
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

.frame-82 {
  width: 385px;
  height: 123px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 5px;
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

.classroom-1 {
  width: 144.83px;
  height: 23.47px;
  left: 96.58px;
  top: 31.20px;
  position: absolute;
  overflow: hidden;
}

.logos {
  width: 85.14px;
  height: 85.87px;
  left: -0.43px;
  top: 0px;
  position: absolute;
  overflow: hidden;
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

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2 {
  width: 20.31px;
  height: 20.31px;
  left: 11.85px;
  top: 13px;
  position: absolute;
  overflow: hidden;
}

.print_24dp_000000_fill0_wght400_grad0_opsz24-1 {
  width: 20px;
  height: 20px;
  left: 0px;
  top: 0px;
  position: absolute;
  overflow: hidden;
}

.icon {
  width: 24.20px;
  height: 26.62px;
  overflow: hidden;
  justify-content: flex-start;
  align-items: flex-start;
  display: flex;
}

.frame-4 {
  width: 39.17px;
  height: 32px;
  justify-content: flex-start;
  align-items: center;
  gap: 70.38px;
  display: flex;
}

.glyph_01 {
  width: 20px;
  height: 20px;
  position: relative;
  overflow: hidden;
}

.icon_07 {
  width: 25.42px;
  height: 24px;
  overflow: hidden;
  justify-content: center;
  align-items: center;
  display: flex;
}

.icon_08 {
  width: 25.42px;
  height: 24px;
  overflow: hidden;
  justify-content: center;
  align-items: center;
  display: flex;
}

.icon_09 {
  width: 25.42px;
  height: 24px;
  overflow: hidden;
  justify-content: center;
  align-items: center;
  display: flex;
}

.icon_10 {
  width: 25.42px;
  height: 24px;
  overflow: hidden;
  justify-content: center;
  align-items: center;
  display: flex;
}

.icon_11 {
  width: 25.42px;
  height: 24px;
  overflow: hidden;
  justify-content: center;
  align-items: center;
  display: flex;
}

.icon_12 {
  width: 25.42px;
  height: 24px;
  overflow: hidden;
  justify-content: center;
  align-items: center;
  display: flex;
}

.icon_13 {
  width: 25.42px;
  height: 24px;
  overflow: hidden;
  justify-content: center;
  align-items: center;
  display: flex;
}

.icon_14 {
  width: 25.42px;
  height: 24px;
  overflow: hidden;
  justify-content: center;
  align-items: center;
  display: flex;
}

.icon_15 {
  width: 25.42px;
  height: 24px;
  overflow: hidden;
  justify-content: center;
  align-items: center;
  display: flex;
}

.icon_16 {
  width: 25.42px;
  height: 24px;
  overflow: hidden;
  justify-content: center;
  align-items: center;
  display: flex;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_01 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_02 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_03 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_04 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
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

.pills {
  width: 515px;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.materials {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-end;
  align-items: flex-start;
  gap: 10px;
  display: flex;
}

.text-icon {
  align-self: stretch;
  justify-content: space-between;
  align-items: center;
  display: inline-flex;
}

.text-icon_01 {
  align-self: stretch;
  justify-content: space-between;
  align-items: center;
  display: inline-flex;
}

.text-icon_02 {
  align-self: stretch;
  justify-content: space-between;
  align-items: center;
  display: inline-flex;
}

.text-icon_03 {
  align-self: stretch;
  justify-content: space-between;
  align-items: center;
  display: inline-flex;
}

.text-icon_04 {
  align-self: stretch;
  justify-content: space-between;
  align-items: center;
  display: inline-flex;
}

.text-icon_05 {
  align-self: stretch;
  justify-content: space-between;
  align-items: center;
  display: inline-flex;
}

.frame-832 {
  align-self: stretch;
  height: 122px;
  padding-left: 32px;
  padding-right: 32px;
  padding-top: 16px;
  padding-bottom: 16px;
  background: var(--SFH-Green, #349552);
  overflow: hidden;
  border-radius: 20px;
  justify-content: space-between;
  align-items: center;
  display: inline-flex;
}

.name {
  justify-content: flex-start;
  align-items: center;
  gap: 8px;
  display: flex;
}

.frame-1043 {
  align-self: stretch;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-817 {
  justify-content: flex-start;
  align-items: center;
  gap: 8px;
  display: flex;
}

.name_02 {
  justify-content: flex-start;
  align-items: center;
  gap: 8px;
  display: flex;
}

.frame-1043_01 {
  align-self: stretch;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.header-button {
  align-self: stretch;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
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

.frame-109_01 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_02 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_03 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-79 {
  width: 385px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 39px;
  display: flex;
}

.logo {
  width: 244.11px;
  height: 85.87px;
  left: 30.75px;
  top: 14.84px;
  position: absolute;
}

.icon_favorite {
  width: 44px;
  height: 44px;
  position: relative;
}

.glyph {
  width: 20px;
  height: 20px;
  position: relative;
  overflow: hidden;
}

.time {
  justify-content: flex-start;
  align-items: center;
  gap: 6px;
  display: inline-flex;
}

.goal-icon {
  justify-content: center;
  align-items: center;
  gap: 61.54px;
  display: inline-flex;
}

.secondary-button_01 {
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

.stars {
  width: 146.66px;
  height: 24px;
  justify-content: flex-start;
  align-items: center;
  gap: 4.89px;
  display: flex;
}

.stars_01 {
  width: 146.66px;
  height: 24px;
  justify-content: flex-start;
  align-items: center;
  gap: 4.89px;
  display: flex;
}

.icon_favorite_01 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_02 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_03 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_04 {
  width: 36px;
  height: 36px;
  position: relative;
}

.accordian {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 24px;
  display: flex;
}

.accordian_01 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 24px;
  display: flex;
}

.accordian_02 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 24px;
  display: flex;
}

.accordian_03 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 24px;
  display: flex;
}

.accordian_04 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 24px;
  display: flex;
}

.accordian_05 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 24px;
  display: flex;
}

.name-image-pills_01 {
  justify-content: flex-start;
  align-items: center;
  gap: 8px;
  display: flex;
}

.copy {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 16px;
  display: flex;
}

.name-and-badge {
  justify-content: flex-start;
  align-items: center;
  gap: 8px;
  display: flex;
}

.name-image-pills_03 {
  justify-content: flex-start;
  align-items: center;
  gap: 8px;
  display: flex;
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

.frame-137 {
  width: 1283px;
  height: 115.56px;
  left: 78.50px;
  top: 72.44px;
  position: absolute;
}

.secondary-button {
  height: 44px;
  padding-top: 5px;
  padding-bottom: 8px;
  padding-left: 24px;
  padding-right: 24px;
  border-radius: 40px;
  outline: 1.50px var(--SFH-White, white) solid;
  outline-offset: -1.50px;
  justify-content: center;
  align-items: center;
  gap: 6px;
  display: flex;
}

.top-info {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 18px;
  display: flex;
}

.goal-icon-circle {
  width: 63px;
  height: 64px;
  left: 333px;
  top: 17.76px;
  position: absolute;
  background: var(--04_Quality-Education, #C5192D);
  overflow: hidden;
  border-radius: 82.57px;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  display: inline-flex;
}

.frame-1044 {
  width: 849px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_01 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_02 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_03 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-972 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 32px;
  display: flex;
}

.name-image-pills {
  flex: 1 1 0;
  justify-content: space-between;
  align-items: center;
  display: flex;
}

.name-and-star-container {
  align-self: stretch;
  justify-content: space-between;
  align-items: center;
  display: inline-flex;
}

.name-image-pills_02 {
  flex: 1 1 0;
  justify-content: space-between;
  align-items: center;
  display: flex;
}

.navigation-headerfooter {
  align-self: stretch;
  height: 531px;
  position: relative;
  background: linear-gradient(360deg, rgba(2.02, 56.75, 2.02, 0.60) 0%, rgba(52, 152, 70, 0) 100%), var(--SFH-Green, #349552);
  overflow: hidden;
}

.navigation-header {
  align-self: stretch;
  height: 188px;
  position: relative;
}

.favorite-button {
  left: 1036.50px;
  top: 30px;
  position: absolute;
  background: var(--04_Quality-Education, #C5192D);
  justify-content: flex-end;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
}

.text-left {
  width: 850px;
  height: 446px;
  padding: 40px;
  left: 0px;
  top: 0px;
  position: absolute;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.goal-overview {
  width: 414px;
  height: 227px;
  left: 869.28px;
  top: 219px;
  position: absolute;
  background: #EEEAE5;
  border-top-left-radius: 10px;
  border-top-right-radius: 20px;
  border-bottom-right-radius: 20px;
  border-bottom-left-radius: 20px;
}

.frame-154 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_01 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_02 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_03 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.accordians {
  width: 1286px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 32px;
  display: flex;
}

.name-stars {
  align-self: stretch;
  justify-content: space-between;
  align-items: center;
  display: inline-flex;
}

.user-review {
  width: 631px;
  padding: 24px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--SFH-Cream-Dark, #EEEAE5) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 16px;
  display: flex;
}

.name-stars_01 {
  align-self: stretch;
  justify-content: space-between;
  align-items: center;
  display: inline-flex;
}

.lesson-header-desktop {
  width: 1283.50px;
  height: 446.22px;
  position: relative;
}

.lesson-card {
  width: 306.25px;
  height: 214px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--06_Clean-Water, #26BDE2) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_01 {
  width: 306.25px;
  height: 214px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px #F2BA44 solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_02 {
  width: 306.25px;
  height: 214px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--08_Decent-Work, #A21942) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_03 {
  width: 306.25px;
  height: 214px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--05_Gender-Equality, #FF3A21) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.review_01 {
  align-self: stretch;
  padding: 32px;
  background: var(--SFH-Cream, #FDF9F1);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--SFH-Cream-Dark, #EEEAE5) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 16px;
  display: flex;
}

.review_03 {
  align-self: stretch;
  padding: 32px;
  background: var(--SFH-Cream, #FDF9F1);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--SFH-Cream-Dark, #EEEAE5) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 16px;
  display: flex;
}

.cards {
  align-self: stretch;
  justify-content: center;
  align-items: flex-start;
  gap: 20px;
  display: inline-flex;
}

.frame-836 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 12px;
  display: flex;
}

.header-button-cards {
  width: 1284px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  gap: 40px;
  display: flex;
}

.frame-837 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 24px;
  display: flex;
}

.featured-lessons {
  align-self: stretch;
  padding-top: 80px;
  padding-bottom: 80px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  gap: 10px;
  display: flex;
}

.frame-838 {
  width: 849px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 24px;
  display: flex;
}

.frame-1045 {
  width: 849px;
  left: 79px;
  top: 80px;
  position: absolute;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 45px;
  display: inline-flex;
}

.reviewdesktop {
  align-self: stretch;
  height: 1078.08px;
  position: relative;
  background: var(--SFH-White, white);
  overflow: hidden;
}

.bottom-of-page {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  display: flex;
}

.lesson-closed {
  width: 1440px;
  height: 3409px;
  background: #FDF9F1;
  overflow: hidden;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  gap: 60px;
  display: inline-flex;
}
</style>