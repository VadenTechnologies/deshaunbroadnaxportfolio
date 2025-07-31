<script setup lang="ts">
import { ref } from 'vue'
import { useRouter, useRoute } from 'vue-router'
import Button from 'primevue/button'

const router = useRouter()
const route = useRoute()
const mobileMenuOpen = ref(false)

const toggleMobileMenu = () => {
  mobileMenuOpen.value = !mobileMenuOpen.value
}

const navigateTo = (path: string) => {
  router.push(path)
  mobileMenuOpen.value = false
}

const openGitHub = () => {
  window.open('https://github.com/VadenTechnologies', '_blank')
  mobileMenuOpen.value = false
}

const openLinkedIn = () => {
  window.open('https://www.linkedin.com/in/deshaunbroadnax/', '_blank')
  mobileMenuOpen.value = false
}
</script>

<template>
  <div id="app">
    <!-- Navigation -->
    <nav class="navbar">
      <div class="nav-container">
        <div class="nav-brand">
          <h2 class="brand-text">DeShaun Broadnax</h2>
        </div>

        <!-- Desktop Navigation -->
        <div class="nav-menu">
          <Button
            :class="['nav-link', { active: route.name === 'home' }]"
            label="Home"
            text
            @click="navigateTo('/')"
          />
          <Button
            :class="['nav-link', { active: route.name === 'portfolio' }]"
            label="Portfolio"
            text
            @click="navigateTo('/portfolio')"
          />
          <Button
            class="nav-link nav-social"
            icon="pi pi-github"
            text
            @click="openGitHub"
            aria-label="GitHub"
          />
          <Button
            class="nav-link nav-social"
            icon="pi pi-linkedin"
            text
            @click="openLinkedIn"
            aria-label="LinkedIn"
          />
        </div>

        <!-- Mobile Menu Button -->
        <Button
          class="mobile-menu-btn"
          icon="pi pi-bars"
          text
          @click="toggleMobileMenu"
        />
      </div>

      <!-- Mobile Navigation -->
      <div :class="['mobile-menu', { open: mobileMenuOpen }]">
        <Button
          :class="['mobile-nav-link', { active: route.name === 'home' }]"
          label="Home"
          text
          @click="navigateTo('/')"
        />
        <Button
          :class="['mobile-nav-link', { active: route.name === 'portfolio' }]"
          label="Portfolio"
          text
          @click="navigateTo('/portfolio')"
        />
        <Button
          class="mobile-nav-link mobile-social"
          icon="pi pi-github"
          label="GitHub"
          text
          @click="openGitHub"
        />
        <Button
          class="mobile-nav-link mobile-social"
          icon="pi pi-linkedin"
          label="LinkedIn"
          text
          @click="openLinkedIn"
        />
      </div>
    </nav>

    <!-- Main Content -->
    <main class="main-content">
      <router-view />
    </main>
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  background: linear-gradient(135deg, #000814 0%, #001d3d 50%, #003566 100%);
  min-height: 100vh;
}

#app {
  min-height: 100vh;
}

.navbar {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 1000;
  background: rgba(0, 8, 20, 0.9);
  backdrop-filter: blur(20px);
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
  padding: 0.75rem 0;
}

.nav-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav-brand {
  display: flex;
  align-items: center;
}

.brand-text {
  font-size: 1.5rem;
  font-weight: 700;
  background: linear-gradient(135deg, #40e0ff, #8a2be2);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.nav-menu {
  display: flex;
  gap: 1rem;
}

.nav-link {
  color: rgba(255, 255, 255, 0.8) !important;
  font-weight: 500 !important;
  transition: all 0.3s ease !important;
  border: none !important;
  background: transparent !important;
}

.nav-link:hover {
  color: #40e0ff !important;
  transform: translateY(-2px);
}

.nav-link.active {
  color: #40e0ff !important;
  border-radius: 8px !important;
}

.nav-social {
  padding: 0.5rem !important;
  min-width: auto !important;
  width: auto !important;
}

.nav-social:hover {
  color: #40e0ff !important;
  transform: translateY(-2px) scale(1.1) !important;
}

.mobile-menu-btn {
  display: none;
  color: white !important;
  background: transparent !important;
  border: none !important;
}

.mobile-menu {
  display: none;
  flex-direction: column;
  background: rgba(0, 8, 20, 0.95);
  backdrop-filter: blur(20px);
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  padding: 0 2rem;
  max-height: 0;
  overflow: hidden;
  transition: all 0.3s ease;
  opacity: 0;
}

.mobile-menu.open {
  max-height: 280px;
  padding: 1rem 2rem;
  opacity: 1;
}

.mobile-nav-link {
  color: rgba(255, 255, 255, 0.8) !important;
  font-weight: 500 !important;
  margin: 0.5rem 0 !important;
  text-align: left !important;
  justify-content: flex-start !important;
  background: transparent !important;
  border: none !important;
}

.mobile-nav-link:hover,
.mobile-nav-link.active {
  color: #40e0ff !important;
  background: rgba(64, 224, 255, 0.1) !important;
  border-radius: 8px !important;
}

.mobile-social {
  margin-top: 0.5rem !important;
  padding: 0.75rem 1rem !important;
  border-top: 1px solid rgba(255, 255, 255, 0.1) !important;
}

.mobile-social:first-of-type {
  margin-top: 1rem !important;
}

.main-content {
  padding-top: 98px !important;
}

@media (max-width: 768px) {
  .navbar {
    padding: 0.5rem 0;
  }

  .nav-container {
    padding: 0 1rem;
    justify-content: space-between;
    position: relative;
  }

  .nav-brand {
    flex: 1;
    display: flex;
    justify-content: flex-start;
  }

  .nav-menu {
    display: none;
  }

  .mobile-menu-btn {
    display: block;
    flex-shrink: 0;
  }

  .mobile-menu {
    display: flex;
    text-align: left;
  }

  .brand-text {
    font-size: 1.2rem;
  }

  .main-content {
    padding-top: 60px;
  }
}

/* PrimeVue Button Overrides */
.p-button {
  transition: all 0.3s ease !important;
}

.p-button:hover {
  transform: translateY(-2px) !important;
}

/* Scrollbar Styling */
::-webkit-scrollbar {
  width: 8px;
}

::-webkit-scrollbar-track {
  background: rgba(255, 255, 255, 0.1);
}

::-webkit-scrollbar-thumb {
  background: linear-gradient(135deg, #40e0ff, #8a2be2);
  border-radius: 4px;
}

::-webkit-scrollbar-thumb:hover {
  background: linear-gradient(135deg, #60f0ff, #aa4be2);
}
</style>
