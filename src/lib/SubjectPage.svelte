<script lang="ts">
  import Header from './Header.svelte';
  import Footer from './Footer.svelte';

  // Navigation function - will be passed from parent
  export let navigateTo: (page: string) => void = () => {};
</script>

<div class="subject-page-desktop">
  <div class="frame-1145">
    <Header {navigateTo} />
    
    <div class="header-section">
      <div class="frame-1144">
        <div class="creative-writing"><span class="creativewriting_span">Creative          Writing</span></div>
      </div>
      <img class="shape-2" src="/Subject Pages/CreativeWriting-Desktop-Hero.png" alt="Creative Writing Hero" />
    </div>
    
    <div class="frame-1110">
      <div class="frame-149">
        <div class="frame-164">
          <div><span class="grades5-8_span">Grades 5-8</span></div>
        </div>
        <div class="frame-163">
          <div><span class="grades9-12_span">Grades 9-12</span></div>
        </div>
      </div>
      
      <div class="frame-1109">
        <div class="lessons"><span class="lessons_span">Lessons</span></div>
        <div class="grid">
          <!-- Goal 1: No Poverty -->
          <div data-screen-size="Desktop" class="lesson-card">
            <div class="frame-154">
              <div class="frame-153">
                <div class="lesson-title-lorem-ipsum"><span class="lessontitleloremipsum_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite">
                  <div class="ellipse-614"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2">
                    <div class="vector_24"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip"><span class="loremipsumdolorsitametconsecteturadip_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109">
              <div class="lesson-pill">
                <div><span class="creativewriting_span_01">1. No Poverty</span></div>
              </div>
              <div class="lesson-pill_01">
                <div><span class="creativewriting_01_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_02">
                <div><span class="creativewriting_02_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 2: Zero Hunger -->
          <div data-screen-size="Desktop" class="lesson-card_01">
            <div class="frame-154_01">
              <div class="frame-153_01">
                <div class="lesson-title-lorem-ipsum_01"><span class="lessontitleloremipsum_01_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_01">
                  <div class="ellipse-614_01"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_01">
                    <div class="vector_25"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_01"><span class="loremipsumdolorsitametconsecteturadip_01_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_01">
              <div class="lesson-pill_03">
                <div><span class="creativewriting_03_span">2. Zero Hunger</span></div>
              </div>
              <div class="lesson-pill_04">
                <div><span class="creativewriting_04_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_05">
                <div><span class="creativewriting_05_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 3: Good Health & Wellbeing -->
          <div data-screen-size="Desktop" class="lesson-card_02">
            <div class="frame-154_02">
              <div class="frame-153_02">
                <div class="lesson-title-lorem-ipsum_02"><span class="lessontitleloremipsum_02_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_02">
                  <div class="ellipse-614_02"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_02">
                    <div class="vector_26"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_02"><span class="loremipsumdolorsitametconsecteturadip_02_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_02">
              <div class="lesson-pill_06">
                <div><span class="creativewriting_06_span">3. Good Health & Wellbeing</span></div>
              </div>
              <div class="lesson-pill_07">
                <div><span class="creativewriting_07_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_08">
                <div><span class="creativewriting_08_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 4: Quality Education -->
          <div data-screen-size="Desktop" class="lesson-card_03">
            <div class="frame-154_03">
              <div class="frame-153_03">
                <div class="lesson-title-lorem-ipsum_03"><span class="lessontitleloremipsum_03_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_03">
                  <div class="ellipse-614_03"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_03">
                    <div class="vector_27"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_03"><span class="loremipsumdolorsitametconsecteturadip_03_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_03">
              <div class="lesson-pill_09">
                <div><span class="creativewriting_09_span">4. Quality Education</span></div>
              </div>
              <div class="lesson-pill_10">
                <div><span class="creativewriting_10_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_11">
                <div><span class="creativewriting_11_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 5: Gender Equality -->
          <div data-screen-size="Desktop" class="lesson-card_04">
            <div class="frame-154_04">
              <div class="frame-153_04">
                <div class="lesson-title-lorem-ipsum_04"><span class="lessontitleloremipsum_04_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_04">
                  <div class="ellipse-614_04"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_04">
                    <div class="vector_28"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_04"><span class="loremipsumdolorsitametconsecteturadip_04_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_04">
              <div class="lesson-pill_12">
                <div><span class="creativewriting_12_span">5. Gender Equality</span></div>
              </div>
              <div class="lesson-pill_13">
                <div><span class="creativewriting_13_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_14">
                <div><span class="creativewriting_14_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 6: Clean Water & Sanitation -->
          <div data-screen-size="Desktop" class="lesson-card_05">
            <div class="frame-154_05">
              <div class="frame-153_05">
                <div class="lesson-title-lorem-ipsum_05"><span class="lessontitleloremipsum_05_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_05">
                  <div class="ellipse-614_05"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_05">
                    <div class="vector_29"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_05"><span class="loremipsumdolorsitametconsecteturadip_05_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_05">
              <div class="lesson-pill_15">
                <div><span class="creativewriting_15_span">6. Clean Water & Sanitation</span></div>
              </div>
              <div class="lesson-pill_16">
                <div><span class="creativewriting_16_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_17">
                <div><span class="creativewriting_17_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 7: Affordable & Clean Energy -->
          <div data-screen-size="Desktop" class="lesson-card_06">
            <div class="frame-154_06">
              <div class="frame-153_06">
                <div class="lesson-title-lorem-ipsum_06"><span class="lessontitleloremipsum_06_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_06">
                  <div class="ellipse-614_06"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_06">
                    <div class="vector_30"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_06"><span class="loremipsumdolorsitametconsecteturadip_06_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_06">
              <div class="lesson-pill_18">
                <div><span class="creativewriting_18_span">7. Affordable & Clean Energy</span></div>
              </div>
              <div class="lesson-pill_19">
                <div><span class="creativewriting_19_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_20">
                <div><span class="creativewriting_20_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 8: Decent Work & Economic Growth -->
          <div data-screen-size="Desktop" class="lesson-card_07">
            <div class="frame-154_07">
              <div class="frame-153_07">
                <div class="lesson-title-lorem-ipsum_07"><span class="lessontitleloremipsum_07_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_07">
                  <div class="ellipse-614_07"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_07">
                    <div class="vector_31"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_07"><span class="loremipsumdolorsitametconsecteturadip_07_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_07">
              <div class="lesson-pill_21">
                <div><span class="creativewriting_21_span">8. Decent Work & Economic Growth</span></div>
              </div>
              <div class="lesson-pill_22">
                <div><span class="creativewriting_22_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_23">
                <div><span class="creativewriting_23_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 9: Industry, Innovation & Infrastructure -->
          <div data-screen-size="Desktop" class="lesson-card_08">
            <div class="frame-154_08">
              <div class="frame-153_08">
                <div class="lesson-title-lorem-ipsum_08"><span class="lessontitleloremipsum_08_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_08">
                  <div class="ellipse-614_08"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_08">
                    <div class="vector_32"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_08"><span class="loremipsumdolorsitametconsecteturadip_08_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_08">
              <div class="lesson-pill_24">
                <div><span class="creativewriting_24_span">9. Industry, Innovation & Infrastructure</span></div>
              </div>
              <div class="lesson-pill_25">
                <div><span class="creativewriting_25_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_26">
                <div><span class="creativewriting_26_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 10: Reduced Inequalities -->
          <div data-screen-size="Desktop" class="lesson-card_09">
            <div class="frame-154_09">
              <div class="frame-153_09">
                <div class="lesson-title-lorem-ipsum_09"><span class="lessontitleloremipsum_09_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_09">
                  <div class="ellipse-614_09"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_09">
                    <div class="vector_33"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_09"><span class="loremipsumdolorsitametconsecteturadip_09_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_09">
              <div class="lesson-pill_27">
                <div><span class="creativewriting_27_span">10. Reduced Inequalities</span></div>
              </div>
              <div class="lesson-pill_28">
                <div><span class="creativewriting_28_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_29">
                <div><span class="creativewriting_29_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 11: Sustainable Cities & Communities -->
          <div data-screen-size="Desktop" class="lesson-card_10">
            <div class="frame-154_10">
              <div class="frame-153_10">
                <div class="lesson-title-lorem-ipsum_10"><span class="lessontitleloremipsum_10_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_10">
                  <div class="ellipse-614_10"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_10">
                    <div class="vector_34"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_10"><span class="loremipsumdolorsitametconsecteturadip_10_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_10">
              <div class="lesson-pill_30">
                <div><span class="creativewriting_30_span">11. Sustainable Cities & Communities</span></div>
              </div>
              <div class="lesson-pill_31">
                <div><span class="creativewriting_31_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_32">
                <div><span class="creativewriting_32_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 12: Responsible Consumption & Production -->
          <div data-screen-size="Desktop" class="lesson-card_11">
            <div class="frame-154_11">
              <div class="frame-153_11">
                <div class="lesson-title-lorem-ipsum_11"><span class="lessontitleloremipsum_11_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_11">
                  <div class="ellipse-614_11"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_11">
                    <div class="vector_35"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_11"><span class="loremipsumdolorsitametconsecteturadip_11_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_11">
              <div class="lesson-pill_33">
                <div><span class="creativewriting_33_span">12. Responsible Consumption & Prod...</span></div>
              </div>
              <div class="lesson-pill_34">
                <div><span class="creativewriting_34_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_35">
                <div><span class="creativewriting_35_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 13: Climate Action -->
          <div data-screen-size="Desktop" class="lesson-card_12">
            <div class="frame-154_12">
              <div class="frame-153_12">
                <div class="lesson-title-lorem-ipsum_12"><span class="lessontitleloremipsum_12_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_12">
                  <div class="ellipse-614_12"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_12">
                    <div class="vector_36"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_12"><span class="loremipsumdolorsitametconsecteturadip_12_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_12">
              <div class="lesson-pill_36">
                <div><span class="creativewriting_36_span">13. Climate Action</span></div>
              </div>
              <div class="lesson-pill_37">
                <div><span class="creativewriting_37_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_38">
                <div><span class="creativewriting_38_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 14: Life Below Water -->
          <div data-screen-size="Desktop" class="lesson-card_13">
            <div class="frame-154_13">
              <div class="frame-153_13">
                <div class="lesson-title-lorem-ipsum_13"><span class="lessontitleloremipsum_13_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_13">
                  <div class="ellipse-614_13"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_13">
                    <div class="vector_37"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_13"><span class="loremipsumdolorsitametconsecteturadip_13_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_13">
              <div class="lesson-pill_39">
                <div><span class="creativewriting_39_span">14. Life Below Water</span></div>
              </div>
              <div class="lesson-pill_40">
                <div><span class="creativewriting_40_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_41">
                <div><span class="creativewriting_41_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 15: Life on Land -->
          <div data-screen-size="Desktop" class="lesson-card_14">
            <div class="frame-154_14">
              <div class="frame-153_14">
                <div class="lesson-title-lorem-ipsum_14"><span class="lessontitleloremipsum_14_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_14">
                  <div class="ellipse-614_14"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_14">
                    <div class="vector_38"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_14"><span class="loremipsumdolorsitametconsecteturadip_14_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_14">
              <div class="lesson-pill_42">
                <div><span class="creativewriting_42_span">15. Life on Land</span></div>
              </div>
              <div class="lesson-pill_43">
                <div><span class="creativewriting_43_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_44">
                <div><span class="creativewriting_44_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 16: Peace, Justice & Strong Institutions -->
          <div data-screen-size="Desktop" class="lesson-card_15">
            <div class="frame-154_15">
              <div class="frame-153_15">
                <div class="lesson-title-lorem-ipsum_15"><span class="lessontitleloremipsum_15_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_15">
                  <div class="ellipse-614_15"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_15">
                    <div class="vector_39"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_15"><span class="loremipsumdolorsitametconsecteturadip_15_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_15">
              <div class="lesson-pill_45">
                <div><span class="creativewriting_45_span">16. Peace, Justice & Strong Institutions</span></div>
              </div>
              <div class="lesson-pill_46">
                <div><span class="creativewriting_46_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_47">
                <div><span class="creativewriting_47_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>

          <!-- Goal 17: Partnerships for the Goals -->
          <div data-screen-size="Desktop" class="lesson-card_16">
            <div class="frame-154_16">
              <div class="frame-153_16">
                <div class="lesson-title-lorem-ipsum_16"><span class="lessontitleloremipsum_16_span">Lesson title lorem ipsum</span></div>
                <div data-state="Default" class="icon_favorite_16">
                  <div class="ellipse-614_16"></div>
                  <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_16">
                    <div class="vector_40"></div>
                  </div>
                </div>
              </div>
              <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_16"><span class="loremipsumdolorsitametconsecteturadip_16_span">Lorem ipsum dolor sit amet, consectetur adip</span></div>
            </div>
            <div class="frame-109_16">
              <div class="lesson-pill_48">
                <div><span class="creativewriting_48_span">17. Partnerships for the Goals</span></div>
              </div>
              <div class="lesson-pill_49">
                <div><span class="creativewriting_49_span">Creative Writing</span></div>
              </div>
              <div class="lesson-pill_50">
                <div><span class="creativewriting_50_span">Grades 5-8</span></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <Footer {navigateTo} />
    
    <div class="text"><span class="text_span"> </span></div>
  </div>
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

.creativewriting_span {
  color: white;
  font-size: 84px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 75.60px;
  word-wrap: break-word;
}

.creative-writing {
  width: 525.74px;
  height: 159.84px;
  left: 40.45px;
  top: 40.16px;
  position: absolute;
}

.shape-2 {
  width: 350px;
  height: 350px;
  position: relative;
  transform: rotate(-180deg);
  transform-origin: top left;
  border-radius: 20px;
}

.grades5-8_span {
  color: var(--SFH-Black, black);
  font-size: 22px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 22.44px;
  word-wrap: break-word;
}

.grades9-12_span {
  color: var(--SFH-Black, black);
  font-size: 22px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 22.44px;
  word-wrap: break-word;
}

.lessons_span {
  color: var(--SFH-Black, black);
  font-size: 48px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 43.20px;
  word-wrap: break-word;
}

.lessons {
  width: 469.47px;
  height: 42.01px;
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

.ellipse-614 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--01_No-Poverty, #E5243B) solid;
}

.vector_24 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--01_No-Poverty, #E5243B);
}

.loremipsumdolorsitametconsecteturadip_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip {
  align-self: stretch;
}

.creativewriting_span_01 {
  color: white;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_01_span {
  color: white;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_02_span {
  color: white;
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

.ellipse-614_01 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--02_Zero-Hunger, #DDA63A) solid;
}

.vector_25 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--02_Zero-Hunger, #DDA63A);
}

.loremipsumdolorsitametconsecteturadip_01_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_01 {
  align-self: stretch;
}

.creativewriting_03_span {
  color: black;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_04_span {
  color: black;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_05_span {
  color: black;
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

.ellipse-614_02 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--03_Good-Health-Wellbeing, #4C9F38) solid;
}

.vector_26 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--03_Good-Health-Wellbeing, #4C9F38);
}

.loremipsumdolorsitametconsecteturadip_02_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_02 {
  align-self: stretch;
}

.creativewriting_06_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_07_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_08_span {
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

.ellipse-614_03 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--04_Quality-Education, #C5192D) solid;
}

.vector_27 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--04_Quality-Education, #C5192D);
}

.loremipsumdolorsitametconsecteturadip_03_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_03 {
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

.lessontitleloremipsum_04_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_04 {
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

.vector_28 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--05_Gender-Equality, #FF3A21);
}

.loremipsumdolorsitametconsecteturadip_04_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_04 {
  align-self: stretch;
}

.creativewriting_12_span {
  color: white;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_13_span {
  color: white;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_14_span {
  color: white;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_05_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_05 {
  width: 217px;
}

.ellipse-614_05 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--06_Clean-Water-Sanitation, #26BDE2) solid;
}

.vector_29 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--06_Clean-Water-Sanitation, #26BDE2);
}

.loremipsumdolorsitametconsecteturadip_05_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_05 {
  align-self: stretch;
}

.creativewriting_15_span {
  color: black;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_16_span {
  color: black;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_17_span {
  color: black;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_06_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_06 {
  width: 217px;
}

.ellipse-614_06 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--07_Affordable-Clean-Energy, #F2BA44) solid;
}

.vector_30 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--07_Affordable-Clean-Energy, #F2BA44);
}

.loremipsumdolorsitametconsecteturadip_06_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_06 {
  align-self: stretch;
}

.creativewriting_18_span {
  color: black;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_19_span {
  color: black;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_20_span {
  color: black;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_07_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_07 {
  width: 217px;
}

.ellipse-614_07 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--08_Decent-Work-Economic-Growth, #A21942) solid;
}

.vector_31 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--08_Decent-Work-Economic-Growth, #A21942);
}

.loremipsumdolorsitametconsecteturadip_07_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_07 {
  align-self: stretch;
}

.creativewriting_21_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_22_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_23_span {
  color: var(--SFH-White, white);
  elte: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_08_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_08 {
  width: 217px;
}

.ellipse-614_08 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--09_Industry-Innovation-Infrastructure, #FA6622) solid;
}

.vector_32 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--09_Industry-Innovation-Infrastructure, #FA6622);
}

.loremipsumdolorsitametconsecteturadip_08_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_08 {
  align-self: stretch;
}

.creativewriting_24_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_25_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_26_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_09_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_09 {
  width: 217px;
}

.ellipse-614_09 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--10_Reduced-Inequalities, #DD1367) solid;
}

.vector_33 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--10_Reduced-Inequalities, #DD1367);
}

.loremipsumdolorsitametconsecteturadip_09_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_09 {
  align-self: stretch;
}

.creativewriting_27_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_28_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_29_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_10_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_10 {
  width: 217px;
}

.ellipse-614_10 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--11_Sustainable-Cities-Communities, #FD9D24) solid;
}

.vector_34 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--11_Sustainable-Cities-Communities, #FD9D24);
}

.loremipsumdolorsitametconsecteturadip_10_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_10 {
  align-self: stretch;
}

.creativewriting_30_span {
  color: black;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_31_span {
  color: black;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_32_span {
  color: black;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_11_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_11 {
  width: 217px;
}

.ellipse-614_11 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--12_Responsible-Consumption-Production, #BF8B2E) solid;
}

.vector_35 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--12_Responsible-Consumption-Production, #BF8B2E);
}

.loremipsumdolorsitametconsecteturadip_11_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_11 {
  align-self: stretch;
}

.creativewriting_33_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_34_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_35_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_12_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_12 {
  width: 217px;
}

.ellipse-614_12 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--13_Climate-Action, #3F7E44) solid;
}

.vector_36 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--13_Climate-Action, #3F7E44);
}

.loremipsumdolorsitametconsecteturadip_12_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_12 {
  align-self: stretch;
}

.creativewriting_36_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_37_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_38_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_13_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_13 {
  width: 217px;
}

.ellipse-614_13 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--14_Life-Below-Water, #0A97D9) solid;
}

.vector_37 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--14_Life-Below-Water, #0A97D9);
}

.loremipsumdolorsitametconsecteturadip_13_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_13 {
  align-self: stretch;
}

.creativewriting_39_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_40_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_41_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_14_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_14 {
  width: 217px;
}

.ellipse-614_14 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--15_Life-on-Land, #56C02B) solid;
}

.vector_38 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--15_Life-on-Land, #56C02B);
}

.loremipsumdolorsitametconsecteturadip_14_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_14 {
  align-self: stretch;
}

.creativewriting_42_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_43_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_44_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_15_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_15 {
  width: 217px;
}

.ellipse-614_15 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--16_Peace-Justice-Strong-Institutions, #00689D) solid;
}

.vector_39 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--16_Peace-Justice-Strong-Institutions, #00689D);
}

.loremipsumdolorsitametconsecteturadip_15_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_15 {
  align-self: stretch;
}

.creativewriting_45_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_46_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_47_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.lessontitleloremipsum_16_span {
  color: var(--SFH-Black, black);
  font-size: 32px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 32px;
  word-wrap: break-word;
}

.lesson-title-lorem-ipsum_16 {
  width: 217px;
}

.ellipse-614_16 {
  width: 36px;
  height: 36px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 1.50px var(--17_Partnerships-for-the-Goals, #19486A) solid;
}

.vector_40 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--17_Partnerships-for-the-Goals, #19486A);
}

.loremipsumdolorsitametconsecteturadip_16_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adip_16 {
  align-self: stretch;
}

.creativewriting_48_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_49_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_50_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.text_span {
  color: black;
  font-size: 12px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 12.24px;
  word-wrap: break-word;
}

.text {
  width: 0px;
  height: 12px;
  left: 721.50px;
  top: 1548px;
  position: absolute;
  text-align: center;
}

.frame-1144 {
  width: 914px;
  height: 350px;
  position: relative;
}

.frame-164 {
  flex: 1 1 0;
  padding-left: 262px;
  padding-right: 262px;
  padding-top: 13px;
  padding-bottom: 13px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 10px;
  justify-content: center;
  align-items: center;
  gap: 10px;
  display: flex;
}

.frame-163 {
  flex: 1 1 0;
  padding-left: 260px;
  padding-right: 260px;
  padding-top: 13px;
  padding-bottom: 13px;
  overflow: hidden;
  border-radius: 10px;
  justify-content: center;
  align-items: center;
  gap: 10px;
  display: flex;
}

.lesson-pill {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--01_No-Poverty, #E5243B);
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
  background: var(--01_No-Poverty, #E5243B);
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
  background: var(--01_No-Poverty, #E5243B);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_03 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--02_Zero-Hunger, #DDA63A);
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
  background: var(--02_Zero-Hunger, #DDA63A);
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
  background: var(--02_Zero-Hunger, #DDA63A);
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
  background: var(--03_Good-Health-Wellbeing, #4C9F38);
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
  background: var(--03_Good-Health-Wellbeing, #4C9F38);
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
  background: var(--03_Good-Health-Wellbeing, #4C9F38);
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
  background: var(--04_Quality-Education, #C5192D);
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
  background: var(--04_Quality-Education, #C5192D);
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
  background: var(--04_Quality-Education, #C5192D);
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

.lesson-pill_15 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--06_Clean-Water-Sanitation, #26BDE2);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_16 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--06_Clean-Water-Sanitation, #26BDE2);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_17 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--06_Clean-Water-Sanitation, #26BDE2);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_18 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--07_Affordable-Clean-Energy, #F2BA44);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_19 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--07_Affordable-Clean-Energy, #F2BA44);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_20 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--07_Affordable-Clean-Energy, #F2BA44);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_21 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--08_Decent-Work-Economic-Growth, #A21942);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_22 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--08_Decent-Work-Economic-Growth, #A21942);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_23 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--08_Decent-Work-Economic-Growth, #A21942);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_24 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--09_Industry-Innovation-Infrastructure, #FA6622);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_25 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--09_Industry-Innovation-Infrastructure, #FA6622);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_26 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--09_Industry-Innovation-Infrastructure, #FA6622);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_27 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--10_Reduced-Inequalities, #DD1367);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_28 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--10_Reduced-Inequalities, #DD1367);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_29 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--10_Reduced-Inequalities, #DD1367);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_30 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--11_Sustainable-Cities-Communities, #FD9D24);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_31 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--11_Sustainable-Cities-Communities, #FD9D24);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_32 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--11_Sustainable-Cities-Communities, #FD9D24);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_33 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--12_Responsible-Consumption-Production, #BF8B2E);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_34 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--12_Responsible-Consumption-Production, #BF8B2E);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_35 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--12_Responsible-Consumption-Production, #BF8B2E);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_36 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--13_Climate-Action, #3F7E44);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_37 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--13_Climate-Action, #3F7E44);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_38 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--13_Climate-Action, #3F7E44);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_39 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--14_Life-Below-Water, #0A97D9);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_40 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--14_Life-Below-Water, #0A97D9);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_41 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--14_Life-Below-Water, #0A97D9);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_42 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--15_Life-on-Land, #56C02B);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_43 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--15_Life-on-Land, #56C02B);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_44 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--15_Life-on-Land, #56C02B);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_45 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--16_Peace-Justice-Strong-Institutions, #00689D);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_46 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--16_Peace-Justice-Strong-Institutions, #00689D);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_47 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--16_Peace-Justice-Strong-Institutions, #00689D);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_48 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--17_Partnerships-for-the-Goals, #19486A);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_49 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--17_Partnerships-for-the-Goals, #19486A);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.lesson-pill_50 {
  height: 28px;
  padding-bottom: 2px;
  padding-left: 12px;
  padding-right: 12px;
  background: var(--17_Partnerships-for-the-Goals, #19486A);
  overflow: hidden;
  border-radius: 53px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.header-section {
  justify-content: flex-start;
  align-items: center;
  gap: 21px;
  display: inline-flex;
}

.frame-149 {
  width: 1285px;
  padding: 10px;
  background: #EEEAE5;
  overflow: hidden;
  border-radius: 15px;
  justify-content: flex-start;
  align-items: center;
  gap: 10px;
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

.frame-109_04 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_05 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_06 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_07 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_08 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_09 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_10 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_11 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_12 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_13 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_14 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_15 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.frame-109_16 {
  align-self: stretch;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.icon_favorite {
  width: 36px;
  height: 36px;
  position: relative;
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

.icon_favorite_05 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_06 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_07 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_08 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_09 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_10 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_11 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_12 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_13 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_14 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_15 {
  width: 36px;
  height: 36px;
  position: relative;
}

.icon_favorite_16 {
  width: 36px;
  height: 36px;
  position: relative;
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

.frame-153_04 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_05 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_06 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_07 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_08 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_09 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_10 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_11 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_12 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_13 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_14 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_15 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.frame-153_16 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
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

.frame-154_04 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_05 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_06 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_07 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_08 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_09 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_10 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_11 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_12 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_13 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_14 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_15 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.frame-154_16 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 6px;
  display: flex;
}

.lesson-card {
  width: 306.25px;
  height: 250px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--01_No-Poverty, #E5243B) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_01 {
  width: 306.25px;
  height: 250px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--02_Zero-Hunger, #DDA63A) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_02 {
  width: 306.25px;
  height: 248px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--03_Good-Health-Wellbeing, #4C9F38) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_03 {
  width: 306.25px;
  height: 248px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--04_Quality-Education, #C5192D) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_04 {
  width: 306.25px;
  height: 248px;
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

.lesson-card_05 {
  width: 306.25px;
  height: 248px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--06_Clean-Water-Sanitation, #26BDE2) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_06 {
  width: 306.25px;
  height: 248px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--07_Affordable-Clean-Energy, #F2BA44) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_07 {
  width: 306.25px;
  height: 248px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--08_Decent-Work-Economic-Growth, #A21942) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_08 {
  width: 306.25px;
  height: 248px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--09_Industry-Innovation-Infrastructure, #FA6622) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_09 {
  width: 306.25px;
  height: 248px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--10_Reduced-Inequalities, #DD1367) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_10 {
  width: 306.25px;
  height: 248px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--11_Sustainable-Cities-Communities, #FD9D24) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_11 {
  width: 306.25px;
  height: 248px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--12_Responsible-Consumption-Production, #BF8B2E) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_12 {
  width: 306.25px;
  height: 250px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--13_Climate-Action, #3F7E44) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_13 {
  width: 306.25px;
  height: 248px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--14_Life-Below-Water, #0A97D9) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_14 {
  width: 306.25px;
  height: 250px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--15_Life-on-Land, #56C02B) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_15 {
  width: 306.25px;
  height: 248px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--16_Peace-Justice-Strong-Institutions, #00689D) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_16 {
  width: 306.25px;
  height: 248px;
  padding: 20px;
  background: var(--SFH-White, white);
  overflow: hidden;
  border-radius: 20px;
  outline: 1.50px var(--17_Partnerships-for-the-Goals, #19486A) solid;
  outline-offset: -1.50px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.grid {
  align-self: stretch;
  height: 1330px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  display: inline-flex;
}

.frame-1109 {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 32px;
  display: flex;
}

.frame-1110 {
  width: 1285.50px;
  padding-bottom: 60px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 32px;
  display: flex;
}

.frame-1145 {
  width: 1441.50px;
  left: -1.50px;
  top: 0px;
  position: absolute;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  gap: 40px;
  display: inline-flex;
}

.subject-page-desktop {
  width: 1440px;
  height: 2753px;
  position: relative;
  background: #FDF9F1;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
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

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_05 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_06 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_07 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_08 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_09 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_10 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_11 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_12 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_13 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_14 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_15 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}

.favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_16 {
  width: 16.62px;
  height: 16.62px;
  left: 9.69px;
  top: 10.64px;
  position: absolute;
  overflow: hidden;
}
</style>