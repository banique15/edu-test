<script lang="ts">
  export let navigateTo: (page: string) => void = () => {};
</script>

<footer class="footer">
  <div class="footer-content">
    <!-- Main Footer Section -->
    <div class="footer-main">
      <!-- Left Column - Navigation -->
      <div class="footer-column">
        <h3 class="footer-title">Curriculum</h3>
        <div class="footer-links">
          <button class="footer-link" on:click={() => navigateTo('curriculum')}>Curriculum</button>
          <button class="footer-link" on:click={() => navigateTo('about')}>About</button>
        </div>
        
        <h4 class="footer-subtitle">By Subject</h4>
        <div class="footer-links">
          <div class="footer-link">Visual Art</div>
          <div class="footer-link">Creative Writing</div>
          <div class="footer-link">Dance & Movement</div>
          <div class="footer-link">Music</div>
          <div class="footer-link">Drama</div>
        </div>
        
        <h4 class="footer-subtitle">By Grade</h4>
        <div class="footer-links">
          <div class="footer-link">Grades 5-8</div>
          <div class="footer-link">Grades 9-12</div>
        </div>
      </div>
      
      <!-- Middle Column - SDG Goals -->
      <div class="footer-column">
        <h4 class="footer-subtitle">By Global Goal</h4>
        <div class="sdg-dropdown">
          <div class="dropdown-header">
            <span>Select a goal</span>
            <div class="dropdown-arrow">▼</div>
          </div>
        </div>
        
        <!-- SDG Logo Placeholders -->
        <div class="sdg-logos">
          <div class="sdg-logo-placeholder">SDG 1</div>
          <div class="sdg-logo-placeholder">SDG 2</div>
          <div class="sdg-logo-placeholder">SDG 3</div>
          <div class="sdg-logo-placeholder">SDG 4</div>
          <div class="sdg-logo-placeholder">SDG 5</div>
          <div class="sdg-logo-placeholder">SDG 6</div>
          <div class="sdg-logo-placeholder">SDG 7</div>
          <div class="sdg-logo-placeholder">SDG 8</div>
          <div class="sdg-logo-placeholder">SDG 9</div>
          <div class="sdg-logo-placeholder">SDG 10</div>
          <div class="sdg-logo-placeholder">SDG 11</div>
          <div class="sdg-logo-placeholder">SDG 12</div>
          <div class="sdg-logo-placeholder">SDG 13</div>
          <div class="sdg-logo-placeholder">SDG 14</div>
          <div class="sdg-logo-placeholder">SDG 15</div>
          <div class="sdg-logo-placeholder">SDG 16</div>
          <div class="sdg-logo-placeholder">SDG 17</div>
        </div>
      </div>
      
      <!-- Right Column - About Sing for Hope -->
      <div class="footer-column">
        <div class="about-section">
          <h3 class="about-title">Sing for Hope</h3>
          <p class="about-text">
            Our creative programs bring hope, healing, and connection to millions of people in hospitals, 
            care facilities, schools, refugee camps, transit hubs, and community spaces worldwide.
          </p>
          <button class="learn-more-btn">Learn more</button>
        </div>
        
        <!-- Logo Placeholder -->
        <div class="org-logo">
          <div class="logo-placeholder">
            <div class="logo-icon">🎵</div>
            <span>Sing for Hope Logo</span>
          </div>
        </div>
        
        <!-- Partner Logos Placeholders -->
        <div class="partner-logos">
          <div class="partner-logo-placeholder">Partner 1</div>
          <div class="partner-logo-placeholder">Partner 2</div>
        </div>
      </div>
    </div>
    
    <!-- Footer Bottom -->
    <div class="footer-bottom">
      <p class="copyright">Copyright ©2025 Sing for Hope, Inc. All rights reserved.</p>
    </div>
  </div>
</footer>

<style>
/* Interactive elements */
button {
  cursor: pointer;
  border: none;
  background: none;
  padding: 0;
  margin: 0;
  font: inherit;
  color: inherit;
  text-align: left;
}

.footer-link:hover, 
button.footer-link:hover {
  opacity: 0.8;
  text-decoration: underline;
}

.learn-more-btn:hover {
  transform: translateY(-1px);
  box-shadow: 0 4px 12px rgba(52, 149, 82, 0.3);
}

/* Main Footer Styles */
.footer {
  width: 100%;
  background: var(--SFH-Green, #349552);
  color: white;
  margin: 0;
  padding: 0;
}

.footer-content {
  max-width: 1440px;
  margin: 0 auto;
  padding: 60px 80px 40px;
}

.footer-main {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 80px;
  margin-bottom: 40px;
}

.footer-column {
  display: flex;
  flex-direction: column;
  gap: 24px;
}

/* Typography */
.footer-title {
  font-size: 30px;
  font-family: 'Founders Grotesk', sans-serif;
  font-weight: 400;
  margin: 0 0 16px 0;
  color: white;
}

.footer-subtitle {
  font-size: 20px;
  font-family: 'Founders Grotesk', sans-serif;
  font-weight: 500;
  margin: 0 0 12px 0;
  color: white;
}

.footer-links {
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.footer-link {
  font-size: 18px;
  font-family: 'Founders Grotesk', sans-serif;
  font-weight: 400;
  color: white;
  transition: opacity 0.2s ease;
}

/* SDG Dropdown */
.sdg-dropdown {
  background: white;
  border-radius: 8px;
  padding: 12px 16px;
  margin-bottom: 20px;
}

.dropdown-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: black;
  font-size: 18px;
  font-family: 'Founders Grotesk', sans-serif;
}

.dropdown-arrow {
  font-size: 14px;
  color: black;
}

/* SDG Logos Grid */
.sdg-logos {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  gap: 8px;
  margin-top: 20px;
}

.sdg-logo-placeholder {
  width: 40px;
  height: 40px;
  background: rgba(255, 255, 255, 0.2);
  border-radius: 4px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 10px;
  color: white;
  border: 1px solid rgba(255, 255, 255, 0.3);
}

/* About Section */
.about-section {
  background: white;
  border-radius: 15px;
  padding: 30px;
  color: black;
}

.about-title {
  font-size: 28px;
  font-family: 'Founders Grotesk', sans-serif;
  font-weight: 500;
  margin: 0 0 16px 0;
  color: black;
}

.about-text {
  font-size: 18px;
  font-family: 'Founders Grotesk', sans-serif;
  font-weight: 400;
  line-height: 1.4;
  margin: 0 0 24px 0;
  color: black;
}

.learn-more-btn {
  background: var(--SFH-Green, #349552);
  color: white;
  padding: 12px 24px;
  border-radius: 40px;
  font-size: 18px;
  font-family: 'Founders Grotesk', sans-serif;
  font-weight: 500;
  transition: all 0.3s ease;
}

/* Logo Sections */
.org-logo {
  margin: 20px 0;
}

.logo-placeholder {
  background: rgba(255, 255, 255, 0.2);
  border-radius: 8px;
  padding: 20px;
  text-align: center;
  border: 2px dashed rgba(255, 255, 255, 0.4);
}

.logo-icon {
  font-size: 24px;
  margin-bottom: 8px;
}

.partner-logos {
  display: flex;
  gap: 12px;
}

.partner-logo-placeholder {
  flex: 1;
  background: rgba(255, 255, 255, 0.2);
  border-radius: 8px;
  padding: 16px;
  text-align: center;
  font-size: 14px;
  border: 2px dashed rgba(255, 255, 255, 0.4);
}

/* Footer Bottom */
.footer-bottom {
  border-top: 1px solid rgba(255, 255, 255, 0.2);
  padding-top: 20px;
  text-align: center;
}

.copyright {
  font-size: 14px;
  font-family: 'Proxima Nova', sans-serif;
  color: rgba(255, 255, 255, 0.7);
  margin: 0;
}

/* Responsive Design */
@media (max-width: 1200px) {
  .footer-content {
    padding: 50px 60px 30px;
  }
  
  .footer-main {
    gap: 60px;
  }
}

@media (max-width: 968px) {
  .footer-content {
    padding: 40px 30px 20px;
  }
  
  .footer-main {
    grid-template-columns: 1fr;
    gap: 40px;
  }
  
  .sdg-logos {
    grid-template-columns: repeat(4, 1fr);
  }
}

@media (max-width: 768px) {
  .footer-content {
    padding: 30px 20px 15px;
  }
  
  .footer-title {
    font-size: 24px;
  }
  
  .footer-subtitle {
    font-size: 18px;
  }
  
  .sdg-logos {
    grid-template-columns: repeat(3, 1fr);
  }
  
  .partner-logos {
    flex-direction: column;
  }
}

@media (max-width: 480px) {
  .footer-content {
    padding: 20px 16px 10px;
  }
  
  .about-section {
    padding: 20px;
  }
  
  .about-title {
    font-size: 22px;
  }
  
  .about-text {
    font-size: 16px;
  }
}
</style>