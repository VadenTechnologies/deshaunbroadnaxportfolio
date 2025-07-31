<template>
  <div class="portfolio-container">
    <!-- Header Section -->
    <section class="portfolio-header">
      <div class="header-content">
        <h1 class="portfolio-title">My Portfolio</h1>
        <p class="portfolio-subtitle">Showcasing innovative projects and technical expertise</p>
      </div>
      <div class="header-bg-elements">
        <div class="bg-circle circle-1"></div>
        <div class="bg-circle circle-2"></div>
      </div>
    </section>

    <!-- Talaria Fits Project Section -->
    <section class="project-section talaria-section">
      <div class="project-container">
        <div class="project-layout">
          <div class="project-visual">
            <div class="phone-mockup">
              <div class="phone-frame">
                <div class="phone-speaker"></div>
                <div class="phone-screen">
                  <video
                    class="project-demo-video"
                    autoplay
                    muted
                    loop
                    playsinline
                    poster="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='300' height='600' viewBox='0 0 300 600'%3E%3Crect width='300' height='600' fill='%23001d3d'/%3E%3Ctext x='50%25' y='50%25' dominant-baseline='middle' text-anchor='middle' fill='%2340e0ff' font-family='Arial' font-size='20'%3ETalaria Fits%3C/text%3E%3C/svg%3E"
                  >
                    <source src="https://storage.googleapis.com/vaden-website-assets/screen-20250731-101725.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                  </video>
                </div>
                <div class="phone-power-button"></div>
                <div class="phone-volume-up"></div>
                <div class="phone-volume-down"></div>
                <div class="phone-home-indicator"></div>
              </div>
              <div class="video-overlay"></div>
            </div>
          </div>

          <div class="project-details">
            <div class="project-header">
              <h2 class="project-title">Talaria Fits</h2>
              <p class="project-subtitle">Sneaker Collection & Style Platform</p>
            </div>

            <div class="project-story">
              <h3>Project Challenge</h3>
              <p>
                Inherited a long-delayed project previously derailed by scope creep, disorganized development, and over
                $80,000 in sunk costs. The founder was facing years of stagnation with no viable product to show for the investment.
              </p>

              <h3>The Vision</h3>
              <p>
                Talaria Fits is a mobile app designed for sneaker enthusiasts to track their sneaker collections and discover
                outfit inspirations. Users can catalog their entire sneaker closet and receive personalized styling suggestions
                for each pair, bridging the gap between sneaker collecting and fashion coordination.
              </p>

              <h3>Solution & Impact</h3>
              <p>
                Realigned product vision, organized priorities, and led delivery of a complete MVP — saving the founder thousands
                and turning years of stagnation into momentum. Constructed a full product ecosystem from the ground up.
              </p>
            </div>

            <div class="project-achievements">
              <h3>Key Features & Achievements</h3>
              <ul class="achievement-list">
                <li>Rescued $80,000+ investment from complete loss</li>
                <li>Sneaker collection tracking and cataloging system</li>
                <li>User-friendly mobile interface for sneaker enthusiasts</li>
                <li>Comprehensive admin panel for content management</li>
                <li>Scalable backend architecture on Google Cloud</li>
              </ul>
            </div>

            <div class="tech-stack">
              <h3>Technology Stack</h3>
              <div class="tech-grid">
                <span class="tech-badge primary">React</span>
                <span class="tech-badge">React Native</span>
                <span class="tech-badge">Expo</span>
                <span class="tech-badge">TypeScript</span>
                <span class="tech-badge">iOS</span>
                <span class="tech-badge">Android</span>
                <span class="tech-badge">NestJS</span>
                <span class="tech-badge">Swagger</span>
                <span class="tech-badge">Google Cloud</span>
                <span class="tech-badge">MongoDB</span>
                <span class="tech-badge">API Design</span>
                <span class="tech-badge">API Integration</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Church Everywhere Project Section -->
    <section class="project-section church-section">
      <div class="project-container">
        <div class="project-layout reverse">
          <div class="project-visual">
            <div class="tablet-mockup">
              <div class="tablet-frame">
                <div class="tablet-screen">
                  <video
                    class="project-demo-video tablet-video"
                    autoplay
                    muted
                    loop
                    playsinline
                    poster="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='800' height='600' viewBox='0 0 800 600'%3E%3Crect width='800' height='600' fill='%23001d3d'/%3E%3Ctext x='50%25' y='50%25' dominant-baseline='middle' text-anchor='middle' fill='%2340e0ff' font-family='Arial' font-size='24'%3ECEEMS OS%3C/text%3E%3C/svg%3E"
                  >
                    <source src="https://storage.googleapis.com/vaden-website-assets/Screen_Recording_20250731_111007_CEEMS%20OS.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                  </video>
                </div>
                <div class="tablet-power-button"></div>
                <div class="tablet-volume-up"></div>
                <div class="tablet-volume-down"></div>
              </div>
              <div class="video-overlay"></div>
            </div>
          </div>

          <div class="project-details">
            <div class="project-header">
              <h2 class="project-title">CEEMS</h2>
              <p class="project-subtitle">Church Everywhere Enterprise Management System</p>
            </div>

            <div class="project-story">
              <h3>Project Overview</h3>
              <p>
                Developed a revolutionary tablet-based AV control system for Church Everywhere Technologies that completely
                replaces the Android operating system. CEEMS transforms locked-down tablets into dedicated AV control centers
                for churches, providing seamless control over entire audio-visual systems.
              </p>

              <h3>Technical Innovation</h3>
              <p>
                Rather than building a traditional app, CEEMS replaces the entire Android OS to create a purpose-built,
                locked-down environment. This approach ensures maximum security, eliminates distractions, and provides
                churches with a dedicated, professional-grade AV control solution that can't be compromised by other applications.
              </p>

              <h3>System Architecture</h3>
              <p>
                Built using React with Java integration for deep Android system access, CEEMS provides churches with
                enterprise-level control over their worship technology infrastructure across multiple venues.
              </p>
            </div>

            <div class="project-achievements">
              <h3>Key Features & Capabilities</h3>
              <ul class="achievement-list">
                <li>Complete Android OS replacement for dedicated AV control</li>
                <li>Locked-down tablet environment for security and focus</li>
                <li>Multi-venue audio-visual system management</li>
                <li>Real-time worship service coordination</li>
                <li>Enterprise-grade reliability and performance</li>
                <li>Intuitive touch interface designed for live operations</li>
                <li>Seamless integration with existing church AV infrastructure</li>
              </ul>
            </div>

            <div class="tech-stack">
              <h3>Technology Stack</h3>
              <div class="tech-grid">
                <span class="tech-badge primary">React</span>
                <span class="tech-badge">Java</span>
                <span class="tech-badge">TypeScript</span>
                <span class="tech-badge">IoT</span>
                <span class="tech-badge">AV Systems Integration</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Interactive Code Showcase Section -->
    <section class="code-showcase-section">
      <div class="project-container">
        <div class="showcase-header">
          <h2 class="showcase-title">Interactive Code Showcase</h2>
          <p class="showcase-subtitle">Live mini-projects. Select <code><></code> button to view code.</p>
        </div>

        <div class="mini-projects-grid">
          <!-- Todo App Mini Project -->
          <div class="mini-project-card">
            <div class="project-preview" :class="{ flipped: flippedCards.todo }">
              <div class="preview-front">
                <div class="mini-app-header">
                  <div class="app-title-section">
                    <h3>Todo App</h3>
                    <span class="language-tag vue">Vue</span>
                  </div>
                  <Button
                    icon="pi pi-code"
                    class="flip-btn"
                    @click="flipCard('todo')"
                    text
                  />
                </div>
                <div class="todo-app">
                  <div class="todo-input-section">
                    <input
                      v-model="newTodo"
                      @keyup.enter="addTodo"
                      placeholder="Add a new task..."
                      class="todo-input"
                    />
                    <Button
                      icon="pi pi-plus"
                      @click="addTodo"
                      class="add-btn"
                      size="small"
                    />
                  </div>
                  <div class="todo-list">
                    <div
                      v-for="todo in todos"
                      :key="todo.id"
                      class="todo-item"
                      :class="{ completed: todo.completed }"
                    >
                      <div
                        class="todo-checkbox"
                        :class="{ completed: todo.completed }"
                        @click="toggleTodo(todo.id)"
                      ></div>
                      <span @click="toggleTodo(todo.id)">{{ todo.text }}</span>
                      <Button
                        icon="pi pi-trash"
                        @click="deleteTodo(todo.id)"
                        class="delete-btn"
                        text
                        size="small"
                      />
                    </div>
                  </div>
                </div>
              </div>
              <div class="preview-back">
                <div class="code-header">
                  <h3>Vue 3 Todo App</h3>
                  <Button
                    icon="pi pi-eye"
                    class="flip-btn"
                    @click="flipCard('todo')"
                    text
                  />
                </div>
                <div class="code-content">
                  <pre><code>&lt;script setup&gt;
import { ref } from 'vue'

const todos = ref([
  { id: 1, text: 'Learn Vue 3', completed: true },
  { id: 2, text: 'Build awesome apps', completed: false }
])
const newTodo = ref('')

const addTodo = () => {
  if (newTodo.value.trim()) {
    todos.value.push({
      id: Date.now(),
      text: newTodo.value,
      completed: false
    })
    newTodo.value = ''
  }
}

const toggleTodo = (id) => {
  const todo = todos.value.find(t => t.id === id)
  if (todo) todo.completed = !todo.completed
}

const deleteTodo = (id) => {
  todos.value = todos.value.filter(t => t.id !== id)
}
&lt;/script&gt;</code></pre>
                </div>
              </div>
            </div>
          </div>

          <!-- Weather App Mini Project -->
          <div class="mini-project-card">
            <div class="project-preview" :class="{ flipped: flippedCards.weather }">
              <div class="preview-front">
                <div class="mini-app-header">
                  <div class="app-title-section">
                    <h3>Weather App</h3>
                    <span class="language-tag react">React</span>
                  </div>
                  <Button
                    icon="pi pi-code"
                    class="flip-btn"
                    @click="flipCard('weather')"
                    text
                  />
                </div>
                <div class="weather-app">
                  <div class="weather-card">
                    <div class="weather-icon">☀️</div>
                    <div class="weather-info">
                      <h4>{{ currentLocation }}</h4>
                      <div class="temperature">{{ currentTemp }}°F</div>
                      <div class="description">{{ weatherDesc }}</div>
                      <div v-if="locationStatus" class="location-status">{{ locationStatus }}</div>
                    </div>
                  </div>
                  <div class="weather-details">
                    <div class="detail-item">
                      <span>Humidity</span>
                      <span>{{ humidity }}%</span>
                    </div>
                    <div class="detail-item">
                      <span>Wind</span>
                      <span>{{ windSpeed }} mph</span>
                    </div>
                  </div>
                </div>
              </div>
              <div class="preview-back">
                <div class="code-header">
                  <h3>React Weather Component</h3>
                  <Button
                    icon="pi pi-eye"
                    class="flip-btn"
                    @click="flipCard('weather')"
                    text
                  />
                </div>
                <div class="code-content">
                  <pre><code>const WeatherApp = () => {
  const [weather, setWeather] = useState({
    temp: 78,
    description: 'Sunny',
    location: 'Winter Garden, FL',
    status: ''
  })

  const API_KEY = process.env.REACT_APP_WEATHER_API_KEY

  const getWeatherByCoords = async (lat, lon) => {
    try {
      const response = await fetch(
        `https://api.weatherapi.com/v1/current.json?key=${API_KEY}&q=${lat},${lon}&aqi=no`
      )
      const data = await response.json()

      setWeather({
        temp: Math.round(data.current.temp_f),
        description: data.current.condition.text,
        location: `${data.location.name}, ${data.location.region}`,
        humidity: data.current.humidity,
        windSpeed: Math.round(data.current.wind_mph),
        status: ''
      })
    } catch (error) {
      setWeather(prev => ({
        ...prev,
        status: 'Unable to fetch weather data'
      }))
    }
  }

  const getUserLocation = () => {
    if (!navigator.geolocation) {
      setWeather(prev => ({
        ...prev,
        status: 'Geolocation not supported'
      }))
      return
    }

    navigator.geolocation.getCurrentPosition(
      (position) => {
        const { latitude, longitude } = position.coords
        getWeatherByCoords(latitude, longitude)
      },
      (error) => {
        setWeather(prev => ({
          ...prev,
          status: 'Location access denied. Using default.'
        }))
      }
    )
  }

  useEffect(() => {
    getUserLocation()
  }, [])

  return (
    &lt;div className="weather-card"&gt;
      &lt;div className="weather-icon"&gt;☀️&lt;/div&gt;
      &lt;h4&gt;{weather.location}&lt;/h4&gt;
      &lt;div className="temperature"&gt;{weather.temp}°F&lt;/div&gt;
      &lt;div className="description"&gt;{weather.description}&lt;/div&gt;
      {weather.status && &lt;div className="status"&gt;{weather.status}&lt;/div&gt;}
    &lt;/div&gt;
  )
}</code></pre>
                </div>
              </div>
            </div>
          </div>

          <!-- Calculator Mini Project -->
          <div class="mini-project-card">
            <div class="project-preview" :class="{ flipped: flippedCards.calculator }">
              <div class="preview-front">
                <div class="mini-app-header">
                  <div class="app-title-section">
                    <h3>Calculator</h3>
                    <span class="language-tag javascript">JavaScript</span>
                  </div>
                  <Button
                    icon="pi pi-code"
                    class="flip-btn"
                    @click="flipCard('calculator')"
                    text
                  />
                </div>
                <div class="calculator-app">
                  <div class="calc-display">{{ calcDisplay }}</div>
                  <div class="calc-buttons">
                    <Button label="C" @click="clearCalc" class="calc-btn clear" />
                    <Button label="±" @click="toggleSign" class="calc-btn" />
                    <Button label="%" @click="percentage" class="calc-btn" />
                    <Button label="÷" @click="setOperation('/')" class="calc-btn operator" />

                    <Button label="7" @click="inputNumber('7')" class="calc-btn" />
                    <Button label="8" @click="inputNumber('8')" class="calc-btn" />
                    <Button label="9" @click="inputNumber('9')" class="calc-btn" />
                    <Button label="×" @click="setOperation('*')" class="calc-btn operator" />

                    <Button label="4" @click="inputNumber('4')" class="calc-btn" />
                    <Button label="5" @click="inputNumber('5')" class="calc-btn" />
                    <Button label="6" @click="inputNumber('6')" class="calc-btn" />
                    <Button label="−" @click="setOperation('-')" class="calc-btn operator" />

                    <Button label="1" @click="inputNumber('1')" class="calc-btn" />
                    <Button label="2" @click="inputNumber('2')" class="calc-btn" />
                    <Button label="3" @click="inputNumber('3')" class="calc-btn" />
                    <Button label="+" @click="setOperation('+')" class="calc-btn operator" />

                    <Button label="0" @click="inputNumber('0')" class="calc-btn zero" />
                    <Button label="." @click="inputDecimal" class="calc-btn" />
                    <Button label="=" @click="performCalculation" class="calc-btn equals" />
                  </div>
                </div>
              </div>
              <div class="preview-back">
                <div class="code-header">
                  <h3>JavaScript Calculator</h3>
                  <Button
                    icon="pi pi-eye"
                    class="flip-btn"
                    @click="flipCard('calculator')"
                    text
                  />
                </div>
                <div class="code-content">
                  <pre><code>class Calculator {
  constructor() {
    this.display = '0'
    this.previousValue = null
    this.operation = null
    this.waitingForOperand = false
  }

  inputNumber(num) {
    if (this.waitingForOperand) {
      this.display = num
      this.waitingForOperand = false
    } else {
      this.display = this.display === '0' ? num : this.display + num
    }
  }

  setOperation(nextOperation) {
    const inputValue = parseFloat(this.display)

    if (this.previousValue === null) {
      this.previousValue = inputValue
    } else if (this.operation) {
      const result = this.calculate()
      this.display = String(result)
      this.previousValue = result
    }

    this.waitingForOperand = true
    this.operation = nextOperation
  }

  calculate() {
    const prev = this.previousValue
    const current = parseFloat(this.display)

    switch (this.operation) {
      case '+': return prev + current
      case '-': return prev - current
      case '*': return prev * current
      case '/': return prev / current
      default: return current
    }
  }
}</code></pre>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="showcase-footer">
          <p class="showcase-note">
            <i class="pi pi-github"></i>
            Interactive demos built with Vue 3, React, and vanilla JavaScript
          </p>
          <Button
            label="View More Projects"
            icon="pi pi-external-link"
            class="p-button-outlined github-btn"
            @click="openGitHub"
          />
        </div>
      </div>
    </section>

    <!-- Footer Section -->
    <Footer />

  </div>
</template>

<script setup lang="ts">
import { ref, reactive, onMounted } from 'vue'
import Button from 'primevue/button'
import Footer from '@/components/Footer.vue'

// Card flip states
const flippedCards = reactive({
  todo: false,
  weather: false,
  calculator: false
})

// Todo App State
const todos = ref([
  { id: 1, text: 'Learn Vue 3', completed: true },
  { id: 2, text: 'Build awesome apps', completed: false }
])
const newTodo = ref('')

// Weather App State
const currentTemp = ref(78)
const weatherDesc = ref('Sunny')
const humidity = ref(65)
const windSpeed = ref(8)
const currentLocation = ref('Winter Garden, FL')
const locationStatus = ref('')

// Calculator State
const calcDisplay = ref('0')
const previousValue = ref<number | null>(null)
const operation = ref<string | null>(null)
const waitingForOperand = ref(false)

// Methods
const flipCard = (cardName: keyof typeof flippedCards) => {
  flippedCards[cardName] = !flippedCards[cardName]
}

// Weather App Functions
const WEATHER_API_KEY = '1a55f1c4f3bf433caa2153635253107'

const getWeatherByCoords = async (lat: number, lon: number) => {
  try {
    const response = await fetch(
      `https://api.weatherapi.com/v1/current.json?key=${WEATHER_API_KEY}&q=${lat},${lon}&aqi=no`
    )

    if (!response.ok) {
      throw new Error(`Weather API error: ${response.status}`)
    }

    const data = await response.json()

    currentTemp.value = Math.round(data.current.temp_f)
    weatherDesc.value = data.current.condition.text
    humidity.value = data.current.humidity
    windSpeed.value = Math.round(data.current.wind_mph)
    currentLocation.value = `${data.location.name}, ${data.location.region}`
    locationStatus.value = ''
  } catch (error) {
    console.error('Weather fetch failed:', error)
    locationStatus.value = 'Unable to fetch weather data'
    // Keep default values as fallback
  }
}

const getWeatherByCity = async (city: string) => {
  try {
    const response = await fetch(
      `https://api.weatherapi.com/v1/current.json?key=${WEATHER_API_KEY}&q=${city}&aqi=no`
    )

    if (!response.ok) {
      throw new Error(`Weather API error: ${response.status}`)
    }

    const data = await response.json()

    currentTemp.value = Math.round(data.current.temp_f)
    weatherDesc.value = data.current.condition.text
    humidity.value = data.current.humidity
    windSpeed.value = Math.round(data.current.wind_mph)
    currentLocation.value = `${data.location.name}, ${data.location.region}`
    locationStatus.value = ''
  } catch (error) {
    console.error('Weather fetch failed:', error)
    locationStatus.value = 'Unable to fetch weather data'
    // Keep default values as fallback
  }
}

const getUserLocation = () => {
  if (!navigator.geolocation) {
    locationStatus.value = 'Geolocation not supported. Using Winter Garden, FL'
    getWeatherByCity('Winter Garden, FL')
    return
  }

  locationStatus.value = 'Getting your location...'

  navigator.geolocation.getCurrentPosition(
    async (position) => {
      const { latitude, longitude } = position.coords
      await getWeatherByCoords(latitude, longitude)
    },
    (error) => {
      console.error('Geolocation error:', error)
      locationStatus.value = 'Location access denied. Using Winter Garden, FL'
      getWeatherByCity('Winter Garden, FL')
    },
    {
      timeout: 10000,
      enableHighAccuracy: true
    }
  )
}

const addTodo = () => {
  if (newTodo.value.trim()) {
    todos.value.push({
      id: Date.now(),
      text: newTodo.value,
      completed: false
    })
    newTodo.value = ''
  }
}

const toggleTodo = (id: number) => {
  const todo = todos.value.find(t => t.id === id)
  if (todo) todo.completed = !todo.completed
}

const deleteTodo = (id: number) => {
  todos.value = todos.value.filter(t => t.id !== id)
}

// Calculator Methods
const inputNumber = (num: string) => {
  if (waitingForOperand.value) {
    calcDisplay.value = num
    waitingForOperand.value = false
  } else {
    calcDisplay.value = calcDisplay.value === '0' ? num : calcDisplay.value + num
  }
}

const setOperation = (nextOperation: string) => {
  const inputValue = parseFloat(calcDisplay.value)

  if (previousValue.value === null) {
    previousValue.value = inputValue
  } else if (operation.value) {
    const result = calculate()
    calcDisplay.value = String(result)
    previousValue.value = result
  }

  waitingForOperand.value = true
  operation.value = nextOperation
}

const calculate = () => {
  const prev = previousValue.value!
  const current = parseFloat(calcDisplay.value)

  switch (operation.value) {
    case '+': return prev + current
    case '-': return prev - current
    case '*': return prev * current
    case '/': return prev / current
    default: return current
  }
}

const performCalculation = () => {
  if (previousValue.value !== null && operation.value) {
    const result = calculate()
    calcDisplay.value = String(result)
    previousValue.value = null
    operation.value = null
    waitingForOperand.value = true
  }
}

const clearCalc = () => {
  calcDisplay.value = '0'
  previousValue.value = null
  operation.value = null
  waitingForOperand.value = false
}

const toggleSign = () => {
  calcDisplay.value = String(-parseFloat(calcDisplay.value))
}

const percentage = () => {
  calcDisplay.value = String(parseFloat(calcDisplay.value) / 100)
}

const inputDecimal = () => {
  if (waitingForOperand.value) {
    calcDisplay.value = '0.'
    waitingForOperand.value = false
  } else if (calcDisplay.value.indexOf('.') === -1) {
    calcDisplay.value += '.'
  }
}

const openGitHub = () => {
  window.open('https://github.com/VadenTechnologies', '_blank')
}

// Initialize weather app on component mount
onMounted(() => {
  getUserLocation()
})
</script>

<!--
  All styles have been moved to modular CSS files for better organization:
  - portfolio-layout.css: Main layout and structure
  - project-details.css: Project information styling
  - device-mockups.css: Phone and tablet mockup styles
  - mini-projects.css: Interactive showcase section
  - mini-apps.css: Individual mini-app component styles

  These are imported in main.css for global availability.
-->
