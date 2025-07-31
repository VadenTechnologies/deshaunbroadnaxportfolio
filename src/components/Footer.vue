<template>
  <footer class="footer-section">
    <div class="footer-container">
      <div class="footer-content">
        <div class="footer-info">
          <h3>DeShaun Broadnax</h3>
          <p>Software Engineer • Winter Garden, FL</p>
        </div>
        <div class="footer-links">
          <Button
            label="GitHub"
            icon="pi pi-github"
            class="p-button-text footer-github-btn"
            @click="openGitHub"
          />
          <Button
            label="LinkedIn"
            icon="pi pi-linkedin"
            class="p-button-text footer-linkedin-btn"
            @click="openLinkedIn"
          />
        </div>
      </div>
      <div class="footer-bottom">
        <p>&copy; 2025 DeShaun Broadnax, Currently Seeking Employment.</p>
      </div>
    </div>
  </footer>
</template>

<script setup lang="ts">
import Button from 'primevue/button'

const openGitHub = () => {
  window.open('https://github.com/VadenTechnologies', '_blank')
}

const openLinkedIn = () => {
  window.open('https://www.linkedin.com/in/deshaunbroadnax/', '_blank')
}
</script>

<style scoped>
/* Footer Section */
.footer-section {
  background: linear-gradient(135deg, #000814 0%, #001d3d 100%);
  padding: 3rem 2rem 1rem;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  position: relative;
}

.footer-container {
  max-width: 1200px;
  margin: 0 auto;
}

.footer-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 2rem;
  flex-wrap: wrap;
  gap: 2rem;
}

.footer-info h3 {
  color: white;
  font-size: 1.5rem;
  font-weight: 600;
  margin-bottom: 0.5rem;
}

.footer-info p {
  color: rgba(255, 255, 255, 0.7);
  font-size: 1rem;
}

.footer-links {
  display: flex;
  gap: 1rem;
  align-items: center;
}

.footer-github-btn,
.footer-linkedin-btn {
  color: rgba(255, 255, 255, 0.8) !important;
  transition: all 0.3s ease !important;
  padding: 0.75rem 1.5rem !important;
  border-radius: 25px !important;
}

.footer-github-btn:hover {
  color: white !important;
  background: rgba(255, 255, 255, 0.1) !important;
  transform: translateY(-2px) !important;
}

.footer-linkedin-btn:hover {
  color: #0077b5 !important;
  background: rgba(0, 119, 181, 0.1) !important;
  transform: translateY(-2px) !important;
}

.footer-bottom {
  text-align: center;
  padding-top: 2rem;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
}

.footer-bottom p {
  color: rgba(255, 255, 255, 0.6);
  font-size: 0.9rem;
  margin: 0;
}

@media (max-width: 768px) {
  .footer-content {
    flex-direction: column;
    text-align: center;
    gap: 1.5rem;
  }

  .footer-links {
    justify-content: center;
  }
}
</style>
