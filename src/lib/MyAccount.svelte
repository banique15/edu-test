<script lang="ts">
  import Header from './Header.svelte';
  import Footer from './Footer.svelte';

  export let navigateTo: (page: string) => void;
</script>

<div class="my-account">
  <Header {navigateTo} currentPage="myaccount" />
  
  <div class="page-content">
    <div class="my-account-header">
      <div class="my-account_01"><span class="myaccount_01_span">My Account</span></div>
      <div class="account-overview">
        <div class="frame-231">
          <div class="frame-230">
            <img class="frame-229" src="https://placehold.co/104x104" alt="Profile" />
            <div class="frame-952">
              <div class="amanda-erickson-minneapolis-mn-music"><span class="amandaericksonminneapolismnmusic_span_01">Amanda Erickson<br/></span><span class="amandaericksonminneapolismnmusic_span_02">Minneapolis, MN<br/>Music<br/></span></div>
              <div class="frame-953">
                <div data-size="Regular" data-state="Default" class="filter-pill">
                  <div><span class="f-8_span">Grades 9-12</span></div>
                </div>
                <div data-size="Regular" data-state="Default" class="filter-pill_01">
                  <div><span class="f-8_01_span">Music</span></div>
                </div>
                <div data-size="Regular" data-state="Default" class="filter-pill_02">
                  <div><span class="f-8_02_span">Dance & Movement</span></div>
                </div>
              </div>
            </div>
          </div>
          <div data-size="Large" data-state="Default" class="secondary-button">
            <div><span class="makeanaccount_span">Edit</span></div>
          </div>
        </div>
      </div>
    </div>
    <div class="your-saved-lessons">
      <div class="your-saved-lessons_01"><span class="yoursavedlessons_01_span">Your Saved Lessons</span></div>
      <div class="grid">
        <div data-screen-size="Desktop" class="lesson-card">
          <div class="frame-154">
            <div class="frame-153">
              <div class="lesson-title-lorem-ipsum"><span class="lessontitleloremipsum_span">Unlocking the Flow</span></div>
              <div data-state="Selected" class="icon_favorite"></div>
            </div>
            <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip"><span class="loremipsumdolorsitametconsecteturadip_span">Stream of consciousness writing for a world of quality education</span></div>
          </div>
          <div class="frame-109">
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
        </div>
        <div data-screen-size="Desktop" class="lesson-card_01">
          <div class="frame-154_01">
            <div class="frame-153_01">
              <div class="lesson-title-lorem-ipsum_01"><span class="lessontitleloremipsum_01_span">School of the Future</span></div>
              <div data-state="Selected" class="icon_favorite_01"></div>
            </div>
            <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_01"><span class="loremipsumdolorsitametconsecteturadip_01_span">Envisioning education through futuristic art</span></div>
          </div>
          <div class="frame-109_01">
            <div class="lesson-pill_03">
              <div><span class="creativewriting_03_span">4. Quality Education</span></div>
            </div>
            <div class="lesson-pill_04">
              <div><span class="creativewriting_04_span">Visual Art</span></div>
            </div>
            <div class="lesson-pill_05">
              <div><span class="creativewriting_05_span">Grades 9-12</span></div>
            </div>
          </div>
        </div>
        <div data-screen-size="Desktop" class="lesson-card_02">
          <div class="frame-154_02">
            <div class="frame-153_02">
              <div class="lesson-title-lorem-ipsum_02"><span class="lessontitleloremipsum_02_span">Unleashing Emotions</span></div>
              <div data-state="Selected" class="icon_favorite_02"></div>
            </div>
            <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_02"><span class="loremipsumdolorsitametconsecteturadip_02_span">Exploring gender equality through expressionist art</span></div>
          </div>
          <div class="frame-109_02">
            <div class="lesson-pill_06">
              <div><span class="creativewriting_06_span">5.  Gender Equality</span></div>
            </div>
            <div class="lesson-pill_07">
              <div><span class="creativewriting_07_span">Visual Art</span></div>
            </div>
            <div class="lesson-pill_08">
              <div><span class="creativewriting_08_span">Grades 9-12</span></div>
            </div>
          </div>
        </div>
        <div data-screen-size="Desktop" class="lesson-card_03">
          <div class="frame-154_03">
            <div class="frame-153_03">
              <div class="lesson-title-lorem-ipsum_03"><span class="lessontitleloremipsum_03_span">Fluid Expressions</span></div>
              <div data-state="Selected" class="icon_favorite_03"></div>
            </div>
            <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_03"><span class="loremipsumdolorsitametconsecteturadip_03_span">Painting a vision for clean water and sanitation</span></div>
          </div>
          <div class="frame-109_03">
            <div class="lesson-pill_09">
              <div><span class="creativewriting_09_span">6. Clean Water & Sanitation</span></div>
            </div>
            <div class="lesson-pill_10">
              <div><span class="creativewriting_10_span">Visual Art</span></div>
            </div>
            <div class="lesson-pill_11">
              <div><span class="creativewriting_11_span">Grades 9-12</span></div>
            </div>
          </div>
        </div>
        <div data-screen-size="Desktop" class="lesson-card_04">
          <div class="frame-154_04">
            <div class="frame-153_04">
              <div class="lesson-title-lorem-ipsum_04"><span class="lessontitleloremipsum_04_span">Illuminating the Future</span></div>
              <div data-state="Selected" class="icon_favorite_04"></div>
            </div>
            <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_04"><span class="loremipsumdolorsitametconsecteturadip_04_span">Installation art for affordable and clean energy</span></div>
          </div>
          <div class="frame-109_04">
            <div class="lesson-pill_12">
              <div><span class="creativewriting_12_span">7. Affordable and Clean Energy</span></div>
            </div>
            <div class="lesson-pill_13">
              <div><span class="creativewriting_13_span">Visual Art</span></div>
            </div>
            <div class="lesson-pill_14">
              <div><span class="creativewriting_14_span">Grades 9-12</span></div>
            </div>
          </div>
        </div>
        <div data-screen-size="Desktop" class="lesson-card_05">
          <div class="frame-154_05">
            <div class="frame-153_05">
              <div class="lesson-title-lorem-ipsum_05"><span class="lessontitleloremipsum_05_span">Power of Persuasion</span></div>
              <div data-state="Selected" class="icon_favorite_05"></div>
            </div>
            <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_05"><span class="loremipsumdolorsitametconsecteturadip_05_span">Championing clean energy through creative writing</span></div>
          </div>
          <div class="frame-109_05">
            <div class="lesson-pill_15">
              <div><span class="creativewriting_15_span">7. Affordable and Clean Energy</span></div>
            </div>
            <div class="lesson-pill_16">
              <div><span class="creativewriting_16_span">Creative Writing</span></div>
            </div>
            <div class="lesson-pill_17">
              <div><span class="creativewriting_17_span">Grades 9-12</span></div>
            </div>
          </div>
        </div>
        <div data-screen-size="Desktop" class="lesson-card_06">
          <div class="frame-154_06">
            <div class="frame-153_06">
              <div class="lesson-title-lorem-ipsum_06"><span class="lessontitleloremipsum_06_span">Haiku for Humanity</span></div>
              <div data-state="Selected" class="icon_favorite_06"></div>
            </div>
            <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_06"><span class="loremipsumdolorsitametconsecteturadip_06_span">Exploring decent work and economic growth</span></div>
          </div>
          <div class="frame-109_06">
            <div class="lesson-pill_18">
              <div><span class="creativewriting_18_span">8. Decent Work and Economic Growth</span></div>
            </div>
            <div class="lesson-pill_19">
              <div><span class="creativewriting_19_span">Creative Writing</span></div>
            </div>
            <div class="lesson-pill_20">
              <div><span class="creativewriting_20_span">Grades 9-12</span></div>
            </div>
          </div>
        </div>
        <div data-screen-size="Desktop" class="lesson-card_07">
          <div class="frame-154_07">
            <div class="frame-153_07">
              <div class="lesson-title-lorem-ipsum_07"><span class="lessontitleloremipsum_07_span">Optical Illusions</span></div>
              <div data-state="Selected" class="icon_favorite_07"></div>
            </div>
            <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_07"><span class="loremipsumdolorsitametconsecteturadip_07_span">Seeing the unseens in decent work and economic Growth</span></div>
          </div>
          <div class="frame-109_07">
            <div class="lesson-pill_21">
              <div><span class="creativewriting_21_span">8. Decent Work and Economic Growth</span></div>
            </div>
            <div class="lesson-pill_22">
              <div><span class="creativewriting_22_span">Visual Art</span></div>
            </div>
            <div class="lesson-pill_23">
              <div><span class="creativewriting_23_span">Grades 9-12</span></div>
            </div>
          </div>
        </div>
      </div>
      <div class="frame-1074">
        <div><span class="seemore_span">See more</span></div>
        <div class="vector-25"></div>
      </div>
    </div>
    <div class="recommended-lessons">
      <div class="frame-1076">
        <div><span class="recommendedlessons_01_span">Recommended Lessons</span></div>
        <button data-size="Large" data-state="Default" class="primary-button" on:click={() => navigateTo('curriculum')}>
          <div><span class="makeanaccount_01_span">Browse Curriculum</span></div>
        </button>
      </div>
      <div class="frame-973">
        <div data-screen-size="Desktop" class="lesson-card_08">
          <div class="frame-154_08">
            <div class="frame-153_08">
              <div class="lesson-title-lorem-ipsum_08"><span class="lessontitleloremipsum_08_span">Scripts for Equality</span></div>
              <div data-state="Default" class="icon_favorite_08">
                <div class="ellipse-614_08"></div>
                <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2">
                  <div class="vector_32"></div>
                </div>
              </div>
            </div>
            <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_08"><span class="loremipsumdolorsitametconsecteturadip_08_span">Crafting dialogue for a gender-equal world</span></div>
          </div>
          <div class="frame-109_08">
            <div class="lesson-pill_24">
              <div><span class="creativewriting_24_span">5.  Gender Equality</span></div>
            </div>
            <div class="lesson-pill_25">
              <div><span class="creativewriting_25_span">Creative Writing</span></div>
            </div>
            <div class="lesson-pill_26">
              <div><span class="creativewriting_26_span">Grades 9-12</span></div>
            </div>
          </div>
        </div>
        <div data-screen-size="Desktop" class="lesson-card_09">
          <div class="frame-154_09">
            <div class="frame-153_09">
              <div class="lesson-title-lorem-ipsum_09"><span class="lessontitleloremipsum_09_span">Words that Flow</span></div>
              <div data-state="Default" class="icon_favorite_09">
                <div class="ellipse-614_09"></div>
                <div class="favorite_24dp_000000_fill0_wght400_grad0_opsz24-1-2_01">
                  <div class="vector_33"></div>
                </div>
              </div>
            </div>
            <div class="lorem-ipsum-dolor-sit-amet-consectetur-adip_09"><span class="loremipsumdolorsitametconsecteturadip_09_span">Painting with words to champion clean water and sanitation</span></div>
          </div>
          <div class="frame-109_09">
            <div class="lesson-pill_27">
              <div><span class="creativewriting_27_span">6. Clean Water & Sanitation</span></div>
            </div>
            <div class="lesson-pill_28">
              <div><span class="creativewriting_28_span">Creative Writing</span></div>
            </div>
            <div class="lesson-pill_29">
              <div><span class="creativewriting_29_span">Grades 9-12</span></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <Footer {navigateTo} />
</div>

<style>
.myaccount_01_span {
  color: var(--SFH-Green, #349552);
  font-size: 84px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 75.60px;
  word-wrap: break-word;
}

.my-account_01 {
  align-self: stretch;
  height: 71.51px;
}

.frame-229 {
  width: 104px;
  height: 104px;
  position: relative;
  background: var(--SFH-White, white);
  border-radius: 100px;
}

.amandaericksonminneapolismnmusic_span_01 {
  color: var(--SFH-Black, black);
  font-size: 19.74px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 27px;
  word-wrap: break-word;
}

.amandaericksonminneapolismnmusic_span_02 {
  color: var(--SFH-Black, black);
  font-size: 19.74px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 27px;
  word-wrap: break-word;
}

.amanda-erickson-minneapolis-mn-music {
  width: 324px;
  height: 75px;
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

.f-8_02_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.makeanaccount_span {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 21.60px;
  word-wrap: break-word;
}

.yoursavedlessons_01_span {
  color: var(--SFH-Black, black);
  font-size: 48px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 43.20px;
  word-wrap: break-word;
}

.your-saved-lessons_01 {
  align-self: stretch;
  height: 62px;
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
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_04_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_05_span {
  color: var(--SFH-White, white);
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
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_10_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_11_span {
  color: #030303;
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
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_13_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_14_span {
  color: #030303;
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
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_16_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_17_span {
  color: #030303;
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
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_19_span {
  color: var(--SFH-White, white);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_20_span {
  color: var(--SFH-White, white);
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
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.seemore_span {
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 16.32px;
  word-wrap: break-word;
}

.vector-25 {
  width: 8.31px;
  height: 4.51px;
  outline: 1px var(--SFH-Black, black) solid;
  outline-offset: -0.50px;
}

.recommendedlessons_01_span {
  color: var(--SFH-Black, black);
  font-size: 48px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 43.20px;
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
  border: 1.50px var(--05_Gender-Equality, #FF3A21) solid;
}

.vector_32 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--05_Gender-Equality, #FF3A21);
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
  border: 1.50px var(--06_Clean-Water, #26BDE2) solid;
}

.vector_33 {
  width: 13.85px;
  height: 12.70px;
  left: 1.38px;
  top: 1.83px;
  position: absolute;
  background: var(--06_Clean-Water, #26BDE2);
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
  color: var(--SFH-Black, black);
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_28_span {
  color: #030303;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
}

.creativewriting_29_span {
  color: #030303;
  font-size: 16px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 19.20px;
  word-wrap: break-word;
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

.secondary-button {
  height: 44px;
  padding-top: 5px;
  padding-bottom: 8px;
  padding-left: 24px;
  padding-right: 24px;
  border-radius: 40px;
  outline: 1.50px black solid;
  outline-offset: -1.50px;
  justify-content: center;
  align-items: center;
  gap: 6px;
  display: flex;
}

.icon_favorite {
  width: 36px;
  height: 36px;
  position: relative;
}

.lesson-pill {
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

.lesson-pill_01 {
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

.lesson-pill_02 {
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

.icon_favorite_01 {
  width: 36px;
  height: 36px;
  position: relative;
}

.lesson-pill_03 {
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

.lesson-pill_04 {
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

.lesson-pill_05 {
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

.icon_favorite_02 {
  width: 36px;
  height: 36px;
  position: relative;
}

.lesson-pill_06 {
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

.lesson-pill_07 {
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

.lesson-pill_08 {
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

.icon_favorite_03 {
  width: 36px;
  height: 36px;
  position: relative;
}

.lesson-pill_09 {
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

.lesson-pill_10 {
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

.lesson-pill_11 {
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

.icon_favorite_04 {
  width: 36px;
  height: 36px;
  position: relative;
}

.lesson-pill_12 {
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

.lesson-pill_13 {
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

.lesson-pill_14 {
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

.icon_favorite_05 {
  width: 36px;
  height: 36px;
  position: relative;
}

.lesson-pill_15 {
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

.lesson-pill_16 {
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

.lesson-pill_17 {
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

.icon_favorite_06 {
  width: 36px;
  height: 36px;
  position: relative;
}

.lesson-pill_18 {
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

.lesson-pill_19 {
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

.lesson-pill_20 {
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

.icon_favorite_07 {
  width: 36px;
  height: 36px;
  position: relative;
}

.lesson-pill_21 {
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

.lesson-pill_22 {
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

.lesson-pill_23 {
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
  display: flex;
}

.lesson-pill_24 {
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

.lesson-pill_25 {
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

.lesson-pill_26 {
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

.lesson-pill_27 {
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

.lesson-pill_28 {
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

.lesson-pill_29 {
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

.frame-1074 {
  align-self: stretch;
  padding-top: 24px;
  padding-left: 603px;
  padding-right: 603px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 10px;
  display: flex;
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

.frame-953 {
  justify-content: flex-start;
  align-items: flex-start;
  gap: 8px;
  display: inline-flex;
}

.frame-153 {
  width: 266px;
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

.frame-153_01 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
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

.frame-153_02 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
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

.frame-153_03 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
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

.frame-153_04 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
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

.frame-153_05 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
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

.frame-153_06 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
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

.frame-153_07 {
  width: 266px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
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

.frame-1076 {
  width: 1194px;
  justify-content: space-between;
  align-items: flex-start;
  display: flex;
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

.frame-952 {
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  gap: 16px;
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

.frame-230 {
  justify-content: flex-start;
  align-items: center;
  gap: 32px;
  display: flex;
}

.lesson-card {
  width: 306.25px;
  height: 249px;
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

.lesson-card_01 {
  width: 306.25px;
  height: 249px;
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

.lesson-card_02 {
  width: 306.25px;
  height: 249px;
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

.lesson-card_03 {
  width: 306.25px;
  height: 249px;
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

.lesson-card_04 {
  width: 306.25px;
  height: 249px;
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

.lesson-card_05 {
  width: 306.25px;
  height: 249px;
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

.lesson-card_06 {
  width: 306.25px;
  height: 249px;
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

.lesson-card_07 {
  width: 306.25px;
  height: 249px;
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

.frame-231 {
  width: 1235px;
  justify-content: space-between;
  align-items: flex-start;
  display: inline-flex;
}

.grid {
  align-self: stretch;
  height: 518px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  display: inline-flex;
}

.lesson-card_08 {
  width: 306.25px;
  height: 249px;
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

.lesson-card_09 {
  width: 306.25px;
  height: 249px;
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

.account-overview {
  align-self: stretch;
  padding: 20px;
  background: var(--SFH-White, white);
  border-radius: 20px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 10px;
  display: flex;
}

.your-saved-lessons {
  width: 1285px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 13px;
  display: flex;
}

.frame-973 {
  justify-content: flex-start;
  align-items: center;
  gap: 20px;
  display: flex;
}

.my-account-header {
  width: 1285.06px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 49px;
  display: flex;
}

.recommended-lessons {
  width: 1280.73px;
  padding: 44px;
  background: #EEEAE5;
  overflow: hidden;
  border-radius: 20px;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 358px;
  display: inline-flex;
  flex-wrap: wrap;
  align-content: flex-start;
}

.page-content {
  width: 1440px;
  left: -0.02px;
  top: 258px;
  position: absolute;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  gap: 60px;
  display: inline-flex;
}

.my-account {
  width: 1440px;
  height: 2308px;
  position: relative;
  background: #FDF9F1;
  overflow: hidden;
}
</style>