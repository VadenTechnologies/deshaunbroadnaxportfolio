<template>
  <div class="home-container">
    <!-- Hero Section -->
    <section class="hero-section">
      <!-- Floating Particles -->
      <div class="floating-particles">
        <div class="particle"></div>
        <div class="particle"></div>
        <div class="particle"></div>
        <div class="particle"></div>
        <div class="particle"></div>
      </div>

      <div class="hero-content">
        <div class="profile-section">
          <div class="profile-image-container">
            <img
              src="/assets/headshot.jpg"
              alt="DeShaun Broadnax"
              class="profile-image"
            />
            <div class="image-glow"></div>
          </div>
          <div class="profile-info">
            <h1 class="name-title">DeShaun Broadnax</h1>
            <h2 class="role-title">Software Engineer</h2>
            <p class="bio-text">
              Award winning software engineer with expertise in modern software technologies, 
              creating innovative solutions that make a difference.
            </p>
            <div class="action-buttons">
              <Button
                label="View Portfolio"
                icon="pi pi-briefcase"
                class="p-button-lg portfolio-btn"
                @click="$router.push('/portfolio')"
              />
              <Button
                label="Download Resume"
                icon="pi pi-download"
                class="p-button-lg p-button-outlined resume-btn"
                @click="downloadResume"
              />
              <Button
                label="GitHub"
                icon="pi pi-github"
                class="p-button-lg p-button-outlined github-btn"
                @click="openGitHub"
              />
            </div>
          </div>
        </div>
      </div>
      


      <!-- Animated Background Elements -->
      <div class="bg-elements">
        <div class="floating-element element-1"></div>
        <div class="floating-element element-2"></div>
        <div class="floating-element element-3"></div>
      </div>
    </section>

    <!-- Featured Quotes Section -->
    <section class="featured-quotes-section">
      <div class="container">
        <h2 class="section-title scroll-animate">My Journey & Accomplishments</h2>
        <p class="section-subtitle scroll-animate">A look at my background and key achievements.</p>

        <div class="quotes-grid scroll-animate">
          <!-- Codecademy Quote -->
          <div class="quote-card codecademy-quote">
            <div class="quote-header">
              <div class="quote-source">
                <div class="source-logo codecademy-logo">CC</div>
                <div class="source-info">
                  <h3>Codecademy</h3>
                  <p>Leading Coding Education Platform</p>
                </div>
              </div>
              <i class="pi pi-quote-right quote-icon"></i>
            </div>
            <blockquote class="quote-text">
              "I absolutely love to program. When I was in fourth grade, me and my cousin came up with this business to sell our toys and bikes. I figured that we couldn't have a business without a website, so my first website was for our toy-selling company."
            </blockquote>
            <div class="quote-context">
              <p>From the featured article: <strong>"From Freelance Web Designer to NASA Software Engineer"</strong></p>
              
              <br></br>
              <a
                href="https://www.codecademy.com/resources/blog/from-freelance-web-designer-to-nasa-software-engineer"
                target="_blank"
                class="read-full-article"
              >
                <i class="pi pi-external-link"></i>
                Read Full Article
              </a>
            </div>
          </div>

          <!-- Full Sail Quote -->
          <div class="quote-card fullsail-quote">
            <div class="quote-header">
              <div class="quote-source">
                <div class="source-logo fullsail-logo">FS</div>
                <div class="source-info">
                  <h3>Full Sail University</h3>
                  <p>Innovative Technology Education</p>
                </div>
              </div>
              <i class="pi pi-quote-right quote-icon"></i>
            </div>
            <blockquote class="quote-text">
              "De'Shaun's passion for programming and his Computer Science bachelor's degree from Full Sail University set him on his path to NASA — and his team recently won the Robert H. Goddard Award for their service to the Goddard Space Flight Center."
            </blockquote>
            <div class="quote-context">
              <p>From the featured article: <strong>"Computer Science Grad Working on Apps for NASA's GOES Program"</strong></p>
              <a
                href="https://www.fullsail.edu/about/full-sail-stories/computer-science-grad-working-on-apps-for-nasas-goes-program"
                target="_blank"
                class="read-full-article"
              >
                <i class="pi pi-external-link"></i>
                Read Full Article
              </a>
            </div>
          </div>

          <!-- Achievement Highlight -->
          <div class="quote-card achievement-highlight">
            <div class="achievement-content">
              <div class="achievement-icon">
                <i class="pi pi-trophy"></i>
              </div>
              <h3>Robert H. Goddard Award</h3>
              <p>Recognized for exceptional service to NASA's Goddard Space Flight Center</p>
              <div class="achievement-details">
                <span class="achievement-year">2022</span>
                <span class="achievement-org">NASA Goddard</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Resume Section -->
    <section class="resume-section">
      <div class="section-header scroll-animate">
        <h2 class="section-title">My Resume</h2>
        <p class="section-subtitle">Full Stack Developer • Winter Garden, FL</p>
      </div>

      <div class="resume-container scroll-animate">
        <!-- Contact Info -->
        <div class="contact-info">
          <div class="contact-item">
            <i class="pi pi-map-marker"></i>
            <span>Winter Garden, FL 34787</span>
          </div>
          <div class="contact-item">
            <i class="pi pi-linkedin"></i>
            <a href="https://www.linkedin.com/in/deshaunbroadnax/" target="_blank">
              <span>linkedin.com/in/deshaunb</span>
            </a>
          </div>
        </div>

        <!-- Professional Summary -->
        <div class="summary-card">
          <h3>Professional Summary</h3>
          <p>
            Full-Stack Software Engineer with over 5.5 years of experience leading complete end-to-end software lifecycle for
            projects of all scales. Proven ability to own development from initial product strategy and systems design through to
            hands-on coding and final deployment. Experience spans across diverse environments, from building mission-critical
            systems at NASA to delivering entire product solutions for small business clients in an agile setting.
          </p>
        </div>

        <!-- Skills -->
        <div class="skills-card">
          <h3>Technical Skills</h3>
          <div class="skills-grid">
            <div class="skill-category">
              <h4>Languages</h4>
              <div class="skill-tags">
                <span class="skill-tag">JavaScript</span>
                <span class="skill-tag">TypeScript</span>
                <span class="skill-tag">C#</span>
                <span class="skill-tag">.NET</span>
                <span class="skill-tag">Python</span>
              </div>
            </div>
            <div class="skill-category">
              <h4>Frontend</h4>
              <div class="skill-tags">
                <span class="skill-tag">React</span>
                <span class="skill-tag">Vue.js</span>
                <span class="skill-tag">React Native</span>
                <span class="skill-tag">Angular</span>
              </div>
            </div>
            <div class="skill-category">
              <h4>Backend & Database</h4>
              <div class="skill-tags">
                <span class="skill-tag">Node.js</span>
                <span class="skill-tag">SQL</span>
                <span class="skill-tag">MongoDB</span>
                <span class="skill-tag">PostgreSQL</span>
              </div>
            </div>
            <div class="skill-category">
              <h4>Cloud & Tools</h4>
              <div class="skill-tags">
                <span class="skill-tag">Google Cloud</span>
                <span class="skill-tag">AWS</span>
                <span class="skill-tag">SharePoint</span>
                <span class="skill-tag">Power Platform</span>
                <span class="skill-tag">Content Management Systems</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Experience -->
        <div class="experience-card">
          <h3>Professional Experience</h3>

          <div class="job">
            <div class="job-header">
              <h4>Software Engineer</h4>
              <span class="job-period">July 2021 - Present</span>
            </div>
            <div class="job-company">NASA GOES Program, Embedded Flight Systems Inc.</div>
            <div class="job-location">Goddard Space Flight Center, Greenbelt, MD</div>
            <ul class="job-highlights">
              <li>Served as primary developer for end-to-end design and delivery of multiple internal software tools for the GOES program</li>
              <li>Owned full-stack architecture and development of mission-critical platforms such as G-RASS (Reimbursement Accounting)</li>
              <li>Enabled GOES program to accurately track and manage billions of dollars in transactions</li>
              <li>Architected and developed the NOAA Travel Intake System using M365 PowerApps and SharePoint</li>
              <li>Designed the GOES Event Tracking System used by over 1,000 NASA and NOAA personnel</li>
            </ul>
          </div>

          <div class="job">
            <div class="job-header">
              <h4>Product Owner & Software Architect</h4>
              <span class="job-period">December 2019 - Present</span>
            </div>
            <div class="job-company">Independent Contractor</div>
            <div class="job-location">Remote</div>
            <ul class="job-highlights">
              <li>Drove end-to-end software delivery for private clients and small organizations</li>
              <li>Led client discovery and requirement gathering, aligning software strategy with business goals</li>
              <li>Defined system architectures, selected tech stacks, and directed full implementation cycles</li>
              <li>Conducted investor presentations and product demos to secure funding</li>
            </ul>
          </div>
        </div>

        <!-- Education -->
        <div class="education-card">
          <h3>Education</h3>
          <div class="education-item">
            <h4>Bachelor of Science in Computer Science</h4>
            <div class="education-school">Full Sail University, Winter Park FL</div>
            <div class="education-date">July 2022</div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer Section -->
    <Footer />

  </div>
</template>

<script setup lang="ts">
import { onMounted, onUnmounted } from 'vue'
import Button from 'primevue/button'
import Footer from '@/components/Footer.vue'

const downloadResume = () => {
  const link = document.createElement('a')
  link.href = '/DeShaunBroadnaxResume.pdf'
  link.download = 'DeShaunBroadnaxResume.pdf'
  link.click()
}

const openGitHub = () => {
  window.open('https://github.com/VadenTechnologies', '_blank')
}



// Scroll animation setup
const handleScroll = () => {
  const scrolled = window.pageYOffset
  const rate = scrolled * -0.3

  // Parallax effect for hero content
  const heroContent = document.querySelector('.hero-content') as HTMLElement
  if (heroContent) {
    heroContent.style.transform = `translateY(${rate}px)`
  }

  // Animate elements on scroll
  const animatedElements = document.querySelectorAll('.scroll-animate')
  animatedElements.forEach((element) => {
    const elementTop = element.getBoundingClientRect().top
    const elementVisible = 150

    if (elementTop < window.innerHeight - elementVisible) {
      element.classList.add('animate-in')
    }
  })

  // Update star movement based on scroll
  const scrollPercent = scrolled / (document.body.scrollHeight - window.innerHeight)
  document.documentElement.style.setProperty('--scroll-progress', scrollPercent.toString())
}

onMounted(() => {
  window.addEventListener('scroll', handleScroll)
  // Trigger initial animation check
  handleScroll()
})

onUnmounted(() => {
  window.removeEventListener('scroll', handleScroll)
})
</script>

<style scoped>
.home-container {
  background: linear-gradient(135deg, #000814 0%, #001d3d 50%, #003566 100%);
  position: relative;
  overflow-x: hidden;
}

/* Unified Starfield Background for Hero and Recognition Sections */
.home-container::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 200vh; /* Extended to cover both sections */
  background-image:
    radial-gradient(2px 2px at 20px 30px, #ffffff, transparent),
    radial-gradient(2px 2px at 40px 70px, rgba(255, 255, 255, 0.8), transparent),
    radial-gradient(1px 1px at 90px 40px, #ffffff, transparent),
    radial-gradient(1px 1px at 130px 80px, rgba(255, 255, 255, 0.6), transparent),
    radial-gradient(2px 2px at 160px 30px, #ffffff, transparent),
    radial-gradient(1px 1px at 200px 90px, rgba(255, 255, 255, 0.8), transparent),
    radial-gradient(2px 2px at 240px 50px, #ffffff, transparent),
    radial-gradient(1px 1px at 280px 20px, rgba(255, 255, 255, 0.7), transparent),
    radial-gradient(1px 1px at 320px 100px, #ffffff, transparent),
    radial-gradient(2px 2px at 360px 60px, rgba(255, 255, 255, 0.9), transparent);
  background-repeat: repeat;
  background-size: 400px 120px;
  animation: twinkle 8s ease-in-out infinite alternate, starMove 20s linear infinite;
  pointer-events: none;
  z-index: 1;
}

/* Additional star layers for depth */
.home-container::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 200vh; /* Extended to cover both sections */
  background-image:
    radial-gradient(1px 1px at 50px 60px, rgba(64, 224, 255, 0.8), transparent),
    radial-gradient(1px 1px at 150px 20px, rgba(64, 224, 255, 0.6), transparent),
    radial-gradient(1px 1px at 250px 80px, rgba(64, 224, 255, 0.7), transparent),
    radial-gradient(1px 1px at 350px 40px, rgba(64, 224, 255, 0.5), transparent),
    radial-gradient(2px 2px at 100px 100px, rgba(138, 43, 226, 0.6), transparent),
    radial-gradient(1px 1px at 300px 10px, rgba(138, 43, 226, 0.4), transparent);
  background-repeat: repeat;
  background-size: 500px 140px;
  animation: twinkle 12s ease-in-out infinite alternate-reverse;
  pointer-events: none;
  z-index: 1;
}

.hero-section {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  padding: 2rem;
  z-index: 2;
}

.hero-content {
  max-width: 1200px;
  width: 100%;
  z-index: 3;
  position: relative;
  animation: fadeInUp 1.2s ease-out;
}

.profile-section {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  align-items: center;
}

.profile-image-container {
  position: relative;
  display: flex;
  justify-content: center;
}

.profile-image {
  width: 300px;
  height: 300px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid rgba(255, 255, 255, 0.2);
  box-shadow:
    0 20px 40px rgba(0, 0, 0, 0.6),
    0 0 80px rgba(64, 224, 255, 0.4),
    inset 0 0 30px rgba(255, 255, 255, 0.15);
  transition: all 0.3s ease;
  animation: float 6s ease-in-out infinite;
  position: relative;
  z-index: 3;
}

.profile-image:hover {
  transform: scale(1.05);
  box-shadow:
    0 30px 60px rgba(0, 0, 0, 0.7),
    0 0 120px rgba(64, 224, 255, 0.6),
    inset 0 0 40px rgba(255, 255, 255, 0.25);
}

.image-glow {
  position: absolute;
  top: -20px;
  left: -20px;
  right: -20px;
  bottom: -20px;
  background: radial-gradient(circle, rgba(64, 224, 255, 0.3) 0%, transparent 70%);
  border-radius: 50%;
  animation: pulse 4s ease-in-out infinite;
  z-index: -1;
}

.profile-info {
  color: white;
}

.name-title {
  font-size: 3.5rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
  background: linear-gradient(135deg, #40e0ff, #ffffff, #8a2be2);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  animation: shimmer 3s ease-in-out infinite;
  text-shadow: 0 0 30px rgba(64, 224, 255, 0.5);
  position: relative;
  z-index: 3;
}

.role-title {
  font-size: 1.8rem;
  font-weight: 300;
  margin-bottom: 1.5rem;
  color: rgba(255, 255, 255, 0.8);
}

.bio-text {
  font-size: 1.2rem;
  line-height: 1.6;
  margin-bottom: 2rem;
  color: rgba(255, 255, 255, 0.7);
}

.action-buttons {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.portfolio-btn {
  background: linear-gradient(135deg, #40e0ff, #8a2be2) !important;
  border: none !important;
  box-shadow: 0 8px 25px rgba(64, 224, 255, 0.3) !important;
  transition: all 0.3s ease !important;
}

.portfolio-btn:hover {
  transform: translateY(-2px) !important;
  box-shadow: 0 12px 35px rgba(64, 224, 255, 0.5) !important;
}

.resume-btn {
  border: 2px solid rgba(255, 255, 255, 0.3) !important;
  color: white !important;
  background: rgba(255, 255, 255, 0.1) !important;
  backdrop-filter: blur(10px) !important;
  transition: all 0.3s ease !important;
}

.resume-btn:hover {
  background: rgba(255, 255, 255, 0.2) !important;
  border-color: rgba(255, 255, 255, 0.5) !important;
  transform: translateY(-2px) !important;
}

.github-btn {
  border: 2px solid rgba(255, 255, 255, 0.3) !important;
  color: white !important;
  background: rgba(255, 255, 255, 0.1) !important;
  backdrop-filter: blur(10px) !important;
  transition: all 0.3s ease !important;
}

.github-btn:hover {
  background: rgba(255, 255, 255, 0.2) !important;
  border-color: rgba(255, 255, 255, 0.5) !important;
  transform: translateY(-2px) !important;
}

.featured-articles {
  position: absolute;
  top: 10%;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  flex-direction: row;
  gap: 1.5rem;
  z-index: 3;
}

@media (max-width: 768px) {
  .featured-articles {
    display: none;
  }
}

.article-card {
  background: rgba(255, 255, 255, 0.08);
  backdrop-filter: blur(15px);
  border: 1px solid rgba(255, 255, 255, 0.12);
  border-radius: 15px;
  padding: 1.2rem 1.5rem;
  width: 280px;
  height: 110px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
  transition: all 0.3s ease;
  animation: float 12s ease-in-out infinite;
  display: flex;
  align-items: center;
}

.codecademy-card {
  animation-delay: 2s;
}

.fullsail-card {
  animation-delay: 4s;
}

.article-card:hover {
  transform: translateY(-5px) scale(1.02);
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.25);
  border-color: rgba(64, 224, 255, 0.3);
  background: rgba(255, 255, 255, 0.1);
}

.article-content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  flex: 1;
}

.article-source {
  color: #40e0ff;
  font-size: 0.8rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  margin-bottom: 0.5rem;
}

.article-title {
  color: white;
  font-size: 1rem;
  font-weight: 500;
  line-height: 1.4;
  margin-bottom: 0.6rem;
  display: -webkit-box;
  -webkit-line-clamp: 2;
  line-clamp: 2;
  -webkit-box-orient: vertical;
  overflow: hidden;
}

.article-link {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  color: rgba(255, 255, 255, 0.8);
  text-decoration: none;
  font-size: 0.8rem;
  font-weight: 500;
  transition: all 0.3s ease;
  align-self: flex-start;
}

.article-link:hover {
  color: #40e0ff;
  transform: translateX(2px);
}

.article-link i {
  font-size: 0.7rem;
}

.bg-elements {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 1;
}

.floating-element {
  position: absolute;
  background: linear-gradient(135deg, rgba(64, 224, 255, 0.1), rgba(138, 43, 226, 0.1));
  border-radius: 50%;
  animation: float 8s ease-in-out infinite;
}

.element-1 {
  width: 200px;
  height: 200px;
  top: 10%;
  left: 10%;
  animation-delay: 0s;
}

.element-2 {
  width: 150px;
  height: 150px;
  top: 60%;
  right: 15%;
  animation-delay: 2s;
}

.element-3 {
  width: 100px;
  height: 100px;
  bottom: 20%;
  left: 20%;
  animation-delay: 4s;
}

.resume-section {
  padding: 4rem 2rem;
  background: linear-gradient(135deg, #001d3d 0%, #003566 50%, #000814 100%);
  position: relative;
}

.section-header {
  text-align: center;
  margin-bottom: 3rem;
}

.section-title {
  font-size: 2.5rem;
  font-weight: 700;
  color: white;
  margin-bottom: 0.5rem;
}

.section-subtitle {
  font-size: 1.2rem;
  color: rgba(255, 255, 255, 0.7);
}

.resume-container {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  gap: 2rem;
}

.contact-info {
  display: flex;
  justify-content: center;
  gap: 3rem;
  margin-bottom: 2rem;
  flex-wrap: wrap;
}

.contact-item {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  color: rgba(255, 255, 255, 0.9);
  font-size: 1rem;
}

.contact-item i {
  color: #40e0ff;
  font-size: 1.2rem;
}

.summary-card,
.skills-card,
.experience-card,
.education-card {
  background: rgba(255, 255, 255, 0.05);
  border-radius: 20px;
  padding: 2rem;
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.1);
  transition: all 0.3s ease;
}

.summary-card:hover,
.skills-card:hover,
.experience-card:hover,
.education-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 25px 50px rgba(0, 0, 0, 0.3);
  border-color: rgba(64, 224, 255, 0.3);
}

.summary-card h3,
.skills-card h3,
.experience-card h3,
.education-card h3 {
  color: #40e0ff;
  font-size: 1.5rem;
  margin-bottom: 1.5rem;
  font-weight: 600;
}

.summary-card p {
  color: rgba(255, 255, 255, 0.9);
  line-height: 1.7;
  font-size: 1.1rem;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
}

.skill-category h4 {
  color: rgba(255, 255, 255, 0.9);
  font-size: 1.1rem;
  margin-bottom: 0.8rem;
  font-weight: 500;
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.skill-tag {
  background: linear-gradient(135deg, rgba(64, 224, 255, 0.2), rgba(138, 43, 226, 0.2));
  color: #40e0ff;
  padding: 0.4rem 0.8rem;
  border-radius: 15px;
  font-size: 0.9rem;
  border: 1px solid rgba(64, 224, 255, 0.3);
  transition: all 0.3s ease;
}

.skill-tag:hover {
  background: linear-gradient(135deg, rgba(64, 224, 255, 0.3), rgba(138, 43, 226, 0.3));
  transform: translateY(-2px);
}

.job {
  margin-bottom: 2rem;
  padding-bottom: 2rem;
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
}

.job:last-child {
  border-bottom: none;
  margin-bottom: 0;
}

.job-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 0.5rem;
  flex-wrap: wrap;
}

.job-header h4 {
  color: rgba(255, 255, 255, 0.95);
  font-size: 1.3rem;
  font-weight: 600;
}

.job-period {
  color: #40e0ff;
  font-weight: 500;
  font-size: 1rem;
}

.job-company {
  color: rgba(255, 255, 255, 0.8);
  font-size: 1.1rem;
  font-weight: 500;
  margin-bottom: 0.3rem;
}

.job-location {
  color: rgba(255, 255, 255, 0.6);
  font-size: 1rem;
  margin-bottom: 1rem;
}

.job-highlights {
  list-style: none;
  padding: 0;
}

.job-highlights li {
  color: rgba(255, 255, 255, 0.8);
  line-height: 1.6;
  margin-bottom: 0.8rem;
  padding-left: 1.5rem;
  position: relative;
}

.job-highlights li:before {
  content: "▸";
  color: #40e0ff;
  position: absolute;
  left: 0;
  font-weight: bold;
}

.education-item h4 {
  color: rgba(255, 255, 255, 0.95);
  font-size: 1.2rem;
  font-weight: 600;
  margin-bottom: 0.5rem;
}

.education-school {
  color: rgba(255, 255, 255, 0.8);
  font-size: 1.1rem;
  margin-bottom: 0.3rem;
}

.education-date {
  color: #40e0ff;
  font-weight: 500;
}

@keyframes float {
  0%, 100% { transform: translateY(0px) rotate(0deg); }
  50% { transform: translateY(-20px) rotate(5deg); }
}

@keyframes pulse {
  0%, 100% { opacity: 0.3; transform: scale(1); }
  50% { opacity: 0.6; transform: scale(1.1); }
}

@keyframes shimmer {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}

@media (max-width: 768px) {
  .hero-section {
    padding: 3rem 2rem 2rem;
  }

  .profile-section {
    grid-template-columns: 1fr;
    text-align: center;
    gap: 2rem;
  }

  .name-title {
    font-size: 2.5rem;
  }

  .action-buttons {
    justify-content: center;
  }

  .contact-info {
    grid-template-columns: 1fr;
  }

  .skills-grid {
    grid-template-columns: 1fr;
  }

  .job-header {
    flex-direction: column;
    align-items: flex-start;
    gap: 0.5rem;
  }

  .featured-articles {
    position: static;
    flex-direction: column;
    align-items: center;
    margin-top: 2rem;
    padding: 0 1rem;
    left: auto;
  }

  .article-card {
    width: 100%;
    max-width: 320px;
    height: auto;
    min-height: 80px;
  }

  .article-title {
    font-size: 1rem;
  }
}

@media (max-width: 640px) {
  .featured-articles {
    flex-direction: column;
    align-items: center;
  }

  .article-card {
    width: 100%;
    max-width: 300px;
  }
}

/* Featured Quotes Section */
.featured-quotes-section {
  padding: 6rem 0;
  background: transparent; /* Inherits from home-container */
  position: relative;
}

@keyframes twinkle {
  0% {
    opacity: 0.3;
    transform: scale(1);
  }
  50% {
    opacity: 0.8;
    transform: scale(1.1);
  }
  100% {
    opacity: 0.6;
    transform: scale(1);
  }
}

@keyframes starMove {
  0% {
    transform: translateY(0px);
  }
  100% {
    transform: translateY(-100px);
  }
}

@keyframes slideInFromLeft {
  0% {
    opacity: 0;
    transform: translateX(-100px);
  }
  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes slideInFromRight {
  0% {
    opacity: 0;
    transform: translateX(100px);
  }
  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes fadeInUp {
  0% {
    opacity: 0;
    transform: translateY(50px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes scaleIn {
  0% {
    opacity: 0;
    transform: scale(0.8);
  }
  100% {
    opacity: 1;
    transform: scale(1);
  }
}

@keyframes float {
  0%, 100% {
    transform: translateY(0px);
  }
  50% {
    transform: translateY(-20px);
  }
}

@keyframes floatParticle {
  0% {
    transform: translateY(100vh) translateX(0px) rotate(0deg);
    opacity: 0;
  }
  10% {
    opacity: 1;
  }
  90% {
    opacity: 1;
  }
  100% {
    transform: translateY(-100px) translateX(100px) rotate(360deg);
    opacity: 0;
  }
}

/* Scroll Animation Classes */
.scroll-animate {
  opacity: 0;
  transform: translateY(50px);
  transition: all 0.8s cubic-bezier(0.25, 0.46, 0.45, 0.94);
}

.scroll-animate.animate-in {
  opacity: 1;
  transform: translateY(0);
}

.scroll-animate:nth-child(1) {
  transition-delay: 0.1s;
}

.scroll-animate:nth-child(2) {
  transition-delay: 0.2s;
}

.scroll-animate:nth-child(3) {
  transition-delay: 0.3s;
}

.scroll-animate:nth-child(4) {
  transition-delay: 0.4s;
}

/* Floating Particles */
.floating-particles {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 1;
}

.particle {
  position: absolute;
  width: 4px;
  height: 4px;
  background: rgba(64, 224, 255, 0.8);
  border-radius: 50%;
  animation: floatParticle 15s linear infinite;
}

.particle:nth-child(1) {
  left: 10%;
  animation-delay: 0s;
  animation-duration: 12s;
}

.particle:nth-child(2) {
  left: 25%;
  animation-delay: 2s;
  animation-duration: 18s;
  background: rgba(138, 43, 226, 0.6);
}

.particle:nth-child(3) {
  left: 50%;
  animation-delay: 4s;
  animation-duration: 14s;
}

.particle:nth-child(4) {
  left: 75%;
  animation-delay: 6s;
  animation-duration: 16s;
  background: rgba(255, 255, 255, 0.4);
}

.particle:nth-child(5) {
  left: 90%;
  animation-delay: 8s;
  animation-duration: 20s;
  background: rgba(64, 224, 255, 0.5);
}

.section-title {
  text-align: center;
  font-size: 3rem;
  font-weight: 700;
  background: linear-gradient(135deg, #40e0ff, #ffffff, #8a2be2);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 1rem;
  position: relative;
  z-index: 3;
  text-shadow: 0 0 20px rgba(64, 224, 255, 0.3);
}

.section-subtitle {
  text-align: center;
  font-size: 1.2rem;
  color: rgba(255, 255, 255, 0.9);
  margin-bottom: 4rem;
  position: relative;
  z-index: 3;
  text-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
}

.quotes-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
  max-width: 1200px;
  margin: 0 auto;
}

.quote-card {
  background: rgba(255, 255, 255, 0.08);
  backdrop-filter: blur(25px);
  border: 1px solid rgba(255, 255, 255, 0.15);
  border-radius: 20px;
  padding: 2rem;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
  z-index: 2;
  box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
}

.quote-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: linear-gradient(90deg, #40e0ff, #8a2be2);
  opacity: 0;
  transition: opacity 0.3s ease;
}

.quote-card:hover {
  transform: translateY(-15px);
  box-shadow:
    0 25px 50px rgba(0, 0, 0, 0.4),
    0 0 30px rgba(64, 224, 255, 0.2);
  border-color: rgba(64, 224, 255, 0.4);
  background: rgba(255, 255, 255, 0.12);
}

.quote-card:hover::before {
  opacity: 1;
}

.quote-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 1.5rem;
}

.quote-source {
  display: flex;
  align-items: center;
  gap: 1rem;
}

.source-logo {
  width: 50px;
  height: 50px;
  border-radius: 12px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 700;
  font-size: 1.2rem;
  color: white;
}

.codecademy-logo {
  background: linear-gradient(135deg, #1f4788, #3a6ea5);
}

.fullsail-logo {
  background: linear-gradient(135deg, #ff6b35, #f7931e);
}

.source-info h3 {
  color: white;
  font-size: 1.1rem;
  font-weight: 600;
  margin-bottom: 0.3rem;
}

.source-info p {
  color: rgba(255, 255, 255, 0.6);
  font-size: 0.9rem;
}

.quote-icon {
  color: rgba(64, 224, 255, 0.6);
  font-size: 2rem;
}

.quote-text {
  color: white;
  font-size: 1.1rem;
  line-height: 1.6;
  font-style: italic;
  margin: 0 0 1.5rem 0;
  position: relative;
  padding-left: 1rem;
  border-left: 3px solid rgba(64, 224, 255, 0.3);
}

.quote-context {
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  padding-top: 1rem;
}

.quote-context p {
  color: rgba(255, 255, 255, 0.7);
  font-size: 0.9rem;
  margin-bottom: 1rem;
}

.read-full-article {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  color: #40e0ff;
  text-decoration: none;
  font-size: 0.9rem;
  font-weight: 500;
  transition: all 0.3s ease;
}

.read-full-article:hover {
  color: #60f0ff;
  transform: translateX(5px);
}

/* Achievement Highlight */
.achievement-highlight {
  background: linear-gradient(135deg, rgba(255, 215, 0, 0.1), rgba(64, 224, 255, 0.15));
  border: 2px solid rgba(255, 215, 0, 0.3);
  position: relative;
}

.achievement-highlight::before {
  background: linear-gradient(90deg, #ffd700, #40e0ff);
}

.achievement-highlight:hover {
  box-shadow:
    0 25px 50px rgba(0, 0, 0, 0.4),
    0 0 40px rgba(255, 215, 0, 0.3);
  border-color: rgba(255, 215, 0, 0.5);
}

.achievement-content {
  text-align: center;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.achievement-icon {
  margin-bottom: 1.5rem;
}

.achievement-icon i {
  font-size: 3rem;
  color: #ffd700;
}

.achievement-content h3 {
  color: white;
  font-size: 1.5rem;
  font-weight: 700;
  margin-bottom: 1rem;
}

.achievement-content p {
  color: rgba(255, 255, 255, 0.8);
  font-size: 1rem;
  line-height: 1.5;
  margin-bottom: 1.5rem;
}

.achievement-details {
  display: flex;
  justify-content: center;
  gap: 2rem;
}

.achievement-year,
.achievement-org {
  padding: 0.5rem 1rem;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 20px;
  color: white;
  font-size: 0.9rem;
  font-weight: 600;
}

@media (max-width: 768px) {
  .featured-quotes-section {
    padding: 4rem 1rem;
  }

  .section-title {
    font-size: 2rem;
  }

  .quotes-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }

  .quote-card {
    padding: 1.5rem;
  }

  .quote-header {
    flex-direction: column;
    gap: 1rem;
  }

  .achievement-details {
    flex-direction: column;
    gap: 1rem;
  }
}


</style>
