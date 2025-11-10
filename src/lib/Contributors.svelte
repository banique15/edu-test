<script>
  import '../styles/global.css';
  import Header from './Header.svelte';
  import Footer from './Footer.svelte';

  export let currentPage;
  export let navigateTo;
</script>

<div class="contributors">
  <Header {currentPage} isLoggedIn={false} backgroundColor="green" {navigateTo} />
  
  <div class="header-section">
    <div class="header-copy_01">
      <div class="anything-is-possible-with-the-support-of-our-partners"><span class="anythingispossiblewiththesupportofourpartners_span">Anything is possible with the support of our partners.</span></div>
      <div class="contributors-intro"><span class="contributors-intro_span">The Sing for Hope Global Goals Arts Curriculum was made possible through the generous collaboration of educators, artists, curriculum developers, and advocates who share our vision of empowering young people through creative education. We are deeply grateful for their dedication and expertise.</span></div>
    </div>
    <img class="shape-2" src="/About/about-desktop-block-6.png" alt="Contributors illustration" />
  </div>

  <div class="contributors-section">
    <div class="contributors_02">
      <div class="contributors_03"><span class="contributors_03_span">Contributors</span></div>
      <div class="logo-placeholder_01">
        <div class="partner-logo">
          <div class="partner-name"><span class="partner-name_span">United Nations</span></div>
          <div class="partner-circle un-circle"></div>
        </div>
        <div class="partner-logo">
          <div class="partner-name"><span class="partner-name_span">UNESCO</span></div>
          <div class="partner-circle unesco-circle"></div>
        </div>
        <div class="partner-logo">
          <div class="partner-name"><span class="partner-name_span">National Arts Education Association</span></div>
          <div class="partner-circle naea-circle"></div>
        </div>
        <div class="partner-logo">
          <div class="partner-name"><span class="partner-name_span">Global Partnership for Education</span></div>
          <div class="partner-circle gpe-circle"></div>
        </div>
      </div>
      <div class="contributors-list">
        <div class="column-2">
          <div class="contributor-name"><span class="contributor_span">Dr. Sarah Martinez - Curriculum Developer</span></div>
          <div class="contributor-name"><span class="contributor_span">Prof. Michael Chen - Arts Education Specialist</span></div>
          <div class="contributor-name"><span class="contributor_span">Maria Rodriguez - Visual Arts Educator</span></div>
          <div class="contributor-name"><span class="contributor_span">James Thompson - Music Education Director</span></div>
          <div class="contributor-name"><span class="contributor_span">Dr. Aisha Patel - Global Education Advisor</span></div>
          <div class="contributor-name"><span class="contributor_span">Roberto Silva - Creative Writing Specialist</span></div>
          <div class="contributor-name"><span class="contributor_span">Lisa Johnson - Drama Education Consultant</span></div>
          <div class="contributor-name"><span class="contributor_span">Dr. Ahmed Hassan - Sustainable Development Expert</span></div>
          <div class="contributor-name"><span class="contributor_span">Elena Kowalski - Dance & Movement Educator</span></div>
          <div class="contributor-name"><span class="contributor_span">David Park - Technology Integration Specialist</span></div>
          <div class="contributor-name"><span class="contributor_span">Dr. Grace Okafor - International Education Coordinator</span></div>
          <div class="contributor-name"><span class="contributor_span">Thomas Anderson - Assessment & Evaluation Expert</span></div>
          <div class="contributor-name"><span class="contributor_span">Fatima Al-Rashid - Cultural Diversity Advisor</span></div>
        </div>
        <div class="column-1">
          <div class="contributor-name"><span class="contributor_span">Dr. Priya Sharma - Educational Psychology</span></div>
          <div class="contributor-name"><span class="contributor_span">Carlos Mendez - Community Engagement Specialist</span></div>
          <div class="contributor-name"><span class="contributor_span">Sophie Laurent - French Education Ministry</span></div>
          <div class="contributor-name"><span class="contributor_span">Dr. Kwame Asante - African Studies Scholar</span></div>
          <div class="contributor-name"><span class="contributor_span">Anna Petrov - Eastern European Education Expert</span></div>
          <div class="contributor-name"><span class="contributor_span">Dr. Raj Gupta - STEM Integration Specialist</span></div>
          <div class="contributor-name"><span class="contributor_span">Isabella Romano - Italian Arts Council</span></div>
          <div class="contributor-name"><span class="contributor_span">Dr. Liu Wei - Asia-Pacific Education Director</span></div>
          <div class="contributor-name"><span class="contributor_span">Omar Benjelloun - Middle East Cultural Advisor</span></div>
          <div class="contributor-name"><span class="contributor_span">Dr. Emma Thompson - Child Development Specialist</span></div>
          <div class="contributor-name"><span class="contributor_span">Francisco Gutierrez - Latin American Coordinator</span></div>
          <div class="contributor-name"><span class="contributor_span">Dr. Ingrid Larsson - Nordic Education Research</span></div>
          <div class="contributor-name"><span class="contributor_span">Rachel Green - Accessibility & Inclusion Expert</span></div>
        </div>
      </div>
    </div>
  </div>

  <div class="get-involved-section">
    <div class="get-involved-card-image">
      <div class="text">
        <div class="frame-1135">
          <div class="header-copy">
            <div class="get-involved"><span class="getinvolved_span">Get involved</span></div>
            <div class="get-involved-description"><span class="get-involved-description_span_01">Join our mission to empower young people through arts education and global citizenship. Whether you're an educator, artist, curriculum developer, or advocate, there are many ways to contribute to this transformative initiative. <br/></span><span class="get-involved-description_span_02">Contact us at curriculum@singforhope.org</span></div>
          </div>
        </div>
      </div>
      <img class="image" src="/About/about-desktop-block-5.png" alt="Get involved illustration" />
    </div>
  </div>

  <Footer {navigateTo} />
</div>

<style>
.curriculum_span {
  color: var(--SFH-White, white);
  font-size: 30.68px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 36.75px;
  word-wrap: break-word;
}

.curriculum {
  width: 194.85px;
  left: 78px;
  top: 77.76px;
  position: absolute;
}

.about_span {
  color: var(--SFH-White, white);
  font-size: 24px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 28.75px;
  word-wrap: break-word;
}

.about {
  width: 194.85px;
  left: 293.13px;
  top: 258.76px;
  position: absolute;
}

.contributors_01_span {
  color: var(--SFH-White, white);
  font-size: 24px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 28.75px;
  word-wrap: break-word;
}

.contributors_01 {
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

.creativewriting_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.creative-writing {
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

.makeanaccount_span {
  color: var(--SFH-White, white);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 500;
  line-height: 21.60px;
  word-wrap: break-word;
}

.getinvolved_span {
  color: var(--SFH-Green, #349552);
  font-size: 48px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 43.20px;
  word-wrap: break-word;
}

.get-involved {
  width: 479.50px;
  height: 42px;
}

.loremipsumdolorsitametconsecteturadipiscingelitdonecmaximusturpisegetefficiturfacilisisphasellusvelhendreritestfringillaposuereestinidexinnislpellentesquerhoncusfringillasitametvelitetiametaliquetvelitcontactusatloremsingforhopeorg_span_01 {
  color: rgba(0, 0, 0, 0.60);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.loremipsumdolorsitametconsecteturadipiscingelitdonecmaximusturpisegetefficiturfacilisisphasellusvelhendreritestfringillaposuereestinidexinnislpellentesquerhoncusfringillasitametvelitetiametaliquetvelitcontactusatloremsingforhopeorg_span_02 {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.lorem-ipsum-dolor-sit-amet-consectetur-adipiscing-elit-donec-maximus-turpis-eget-efficitur-facilisis-phasellus-vel-hendrerit-est-fringilla-posuere-est-in-id-ex-in-nisl-pellentesque-rhoncus-fringilla-sit-amet-velit-etiam-et-aliquet-velit-contact-us-at-loremsingforhopeorg {
  align-self: stretch;
}

.image {
  width: 415px;
  height: 272px;
  position: relative;
  transform: rotate(-180deg);
  transform-origin: top left;
  border-radius: 20px;
}

.contributors_03_span {
  color: var(--SFH-Green, #349552);
  font-size: 48px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 43.20px;
  word-wrap: break-word;
}

.contributors_03 {
  align-self: stretch;
  height: 44px;
}

.logoplaceholder_01_span {
  color: black;
  font-size: 16.63px;
  font-family: Founders Grotesk;
  font-weight: 700;
  line-height: 17.96px;
  word-wrap: break-word;
}

.logo-placeholder_01 {
  justify-content: flex-start;
  align-items: center;
  gap: 44px;
  display: inline-flex;
}

.circle {
  width: 44.90px;
  height: 44.90px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 3.33px black solid;
}

.logoplaceholder_03_span {
  color: black;
  font-size: 16.63px;
  font-family: Founders Grotesk;
  font-weight: 700;
  line-height: 17.96px;
  word-wrap: break-word;
}

.logo-placeholder_03 {
  width: 130.55px;
  height: 39.91px;
  left: 50.19px;
  top: 2.49px;
  position: absolute;
}

.circle_01 {
  width: 44.90px;
  height: 44.90px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 3.33px black solid;
}

.logoplaceholder_05_span {
  color: black;
  font-size: 16.63px;
  font-family: Founders Grotesk;
  font-weight: 700;
  line-height: 17.96px;
  word-wrap: break-word;
}

.logo-placeholder_05 {
  width: 130.55px;
  height: 39.91px;
  left: 50.19px;
  top: 2.49px;
  position: absolute;
}

.circle_02 {
  width: 44.90px;
  height: 44.90px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 3.33px black solid;
}

.logoplaceholder_07_span {
  color: black;
  font-size: 16.63px;
  font-family: Founders Grotesk;
  font-weight: 700;
  line-height: 17.96px;
  word-wrap: break-word;
}

.logo-placeholder_07 {
  width: 130.55px;
  height: 39.91px;
  left: 50.19px;
  top: 2.49px;
  position: absolute;
}

.circle_03 {
  width: 44.90px;
  height: 44.90px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 3.33px black solid;
}

.loremipsum_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum {
  align-self: stretch;
  height: 31px;
}

.loremipsum_01_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_01 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_02_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_02 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_03_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_03 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_04_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_04 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_05_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_05 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_06_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_06 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_07_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_07 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_08_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_08 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_09_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_09 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_10_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_10 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_11_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_11 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_12_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_12 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_13_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_13 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_14_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_14 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_15_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_15 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_16_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_16 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_17_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_17 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_18_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_18 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_19_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_19 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_20_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_20 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_21_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_21 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_22_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_22 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_23_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_23 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_24_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_24 {
  align-self: stretch;
  height: 31px;
}

.loremipsum_25_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.lorem-ipsum_25 {
  align-self: stretch;
  height: 31px;
}

.anythingispossiblewiththesupportofourpartners_span {
  color: white;
  font-size: 60px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 54px;
  word-wrap: break-word;
}

.anything-is-possible-with-the-support-of-our-partners {
  width: 750px;
  height: 112px;
}

.loremipsumdolorsitametconsecteturadipiscingelitdonecmaximusturpisegetefficiturfacilisisphasellusvelhendreritestfringillaposuereestinidexinnislpellentesquerhoncusfringillasitametvelitetiametaliquetvelit_span {
  color: rgba(255, 255, 255, 0.80);
  font-size: 24px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 31.20px;
  word-wrap: break-word;
}

.contributors-intro_span {
  color: rgba(255, 255, 255, 0.80);
  font-size: 24px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 31.20px;
  word-wrap: break-word;
}

.contributors-intro {
  width: 844px;
  height: 93px;
}

.shape-2 {
  width: 350px;
  height: 350px;
  left: 1363px;
  top: 576px;
  position: absolute;
  transform: rotate(-180deg);
  transform-origin: top left;
  border-radius: 20px;
}

.header-copy {
  align-self: stretch;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 12px;
  display: flex;
}


.header-copy_01 {
  width: 847px;
  height: 209px;
  left: 77px;
  top: 654px;
  position: absolute;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 12px;
  display: inline-flex;
}

.logo-placeholder {
  width: 172.96px;
  height: 44.90px;
  position: relative;
  overflow: hidden;
}

.logo-placeholder_02 {
  width: 172.96px;
  height: 44.90px;
  position: relative;
  overflow: hidden;
}

.logo-placeholder_04 {
  width: 172.96px;
  height: 44.90px;
  position: relative;
  overflow: hidden;
}

.logo-placeholder_06 {
  width: 172.96px;
  height: 44.90px;
  position: relative;
  overflow: hidden;
}

.frame-1135 {
  align-self: stretch;
  padding: 60px;
  background: var(--SFH-Cream-Dark, #EEEAE5);
  overflow: hidden;
  border-radius: 20px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 10px;
  display: flex;
}

.contributors-list {
  align-self: stretch;
  justify-content: flex-start;
  align-items: center;
  gap: 25px;
  display: inline-flex;
}

.contributor_span {
  color: var(--SFH-Black, black);
  font-size: 20px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 24px;
  word-wrap: break-word;
}

.contributor-name {
  align-self: stretch;
  height: 31px;
}

.partner-name_span {
  color: black;
  font-size: 16.63px;
  font-family: Founders Grotesk;
  font-weight: 700;
  line-height: 17.96px;
  word-wrap: break-word;
}

.partner-name {
  width: 130.55px;
  height: 39.91px;
  left: 50.19px;
  top: 2.49px;
  position: absolute;
}

.partner-logo {
  width: 172.96px;
  height: 44.90px;
  position: relative;
  overflow: hidden;
}

.partner-circle {
  width: 44.90px;
  height: 44.90px;
  left: 0px;
  top: 0px;
  position: absolute;
  border-radius: 9999px;
  border: 3.33px black solid;
}

.un-circle {
  background: #4A90C2;
}

.unesco-circle {
  background: #0077BE;
}

.naea-circle {
  background: #E74C3C;
}

.gpe-circle {
  background: #2ECC71;
}

.get-involved-description_span_01 {
  color: rgba(0, 0, 0, 0.60);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.get-involved-description_span_02 {
  color: var(--SFH-Black, black);
  font-size: 18px;
  font-family: Founders Grotesk;
  font-weight: 400;
  line-height: 21.60px;
  word-wrap: break-word;
}

.get-involved-description {
  align-self: stretch;
}

/* Responsive design improvements */
@media (max-width: 768px) {
  .contributors-section,
  .get-involved-section,
  .header-section {
    padding: 40px 20px;
  }

  .contributors-list {
    flex-direction: column;
    gap: 20px;
  }

  .column-1, .column-2 {
    min-width: 100%;
    max-width: 100%;
  }

  .logo-placeholder_01 {
    flex-direction: column;
    gap: 20px;
  }

  .get-involved-card-image {
    flex-direction: column;
    gap: 30px;
  }

  .text {
    min-width: 100%;
    max-width: 100%;
    text-align: center;
  }

  .image {
    max-width: 100%;
  }

  .anything-is-possible-with-the-support-of-our-partners {
    width: 100%;
  }

  .anythingispossiblewiththesupportofourpartners_span {
    font-size: 36px;
    line-height: 32px;
  }

  .contributors-intro {
    width: 100%;
  }

  .shape-2 {
    width: 100%;
    max-width: 300px;
    height: auto;
  }
}

@media (max-width: 480px) {
  .contributors-section,
  .get-involved-section,
  .header-section {
    padding: 20px 15px;
  }

  .anythingispossiblewiththesupportofourpartners_span {
    font-size: 28px;
    line-height: 26px;
  }

  .contributors-intro_span {
    font-size: 18px;
    line-height: 24px;
  }
}

.header-section {
  width: 100%;
  height: auto;
  position: relative;
  background: var(--SFH-Dark-Green, #1A562C);
  padding: 40px 80px 60px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 40px;
}

.text {
  flex: 1 1 0;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 10px;
  display: inline-flex;
}

.contributors_02 {
  width: 849px;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 48px;
  display: flex;
}

.get-involved-card-image {
  width: 1280px;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 20px;
  display: inline-flex;
}

.contributors-section {
  width: 100%;
  padding: 60px 80px;
  position: relative;
  background: var(--SFH-Cream, #FDF9F1);
  overflow: hidden;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  gap: 60px;
  display: flex;
}

.get-involved-section {
  width: 100%;
  padding: 80px;
  position: relative;
  background: white;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 10px;
  display: flex;
}

.contributors {
  width: 100%;
  min-height: 100vh;
  position: relative;
  background: var(--SFH-Cream, #FDF9F1);
  overflow: hidden;
  display: flex;
  flex-direction: column;
}
</style>