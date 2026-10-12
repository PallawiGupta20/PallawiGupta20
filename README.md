# Hi, I'm Pallawi Gupta 👋
### SDET & Automation Framework Architect

I am a Software Development Engineer in Test (SDET) with **3+ years of professional experience** at **MediaTek** designing, building, and maintaining production-grade, highly optimized End-to-End (E2E) automation ecosystems. I specialize in developing custom multi-layered architectures across Web and Mobile runtime environments using Python, focusing heavily on continuous integration pipelines, request interception setups, and performance analytics.

---

### 🛠️ Core Engineering Stack

* **Web Test Automation:** Playwright • Selenium WebDriver
* **Mobile Test Automation:** Appium (UiAutomator2 Engine for Native & Hybrid)
* **Test Runners & Frameworks:** PyTest • Unittest • API Client Design Patterns
* **Performance & Load Testing:** JMeter
* **Languages & Query Engines:** Python • SQL • HTML • CSS
* **Quality & Test Telemetry:** Allure Reports • Tableau • Power BI Analytics

---

### 📊 Master Test Automation Portfolio

#### 🌐 Web & API Testing Architectures

##### 🧬 [playwright-api-ui-hybrid](https://github.com)
* **Application Under Test:** `automationexercise.com` (Public API & Web Platform)
* **Stack:** Python 3 • Playwright • PyTest • Page Object Model (POM) • GitHub Actions
* **Deep Architecture Implementation:**
  * **API-to-UI Cross-Validation Engine:** Maps asynchronous API Client patterns directly against modular UI Page Objects. Queries REST endpoints using Playwright, parses JSON schemas on the fly, and injects those data variables straight into the UI layer to cross-verify layout rendering fidelity and catch front-end data corruption bugs.
  * **Advanced Network Request Interception:** Built structural request mocking layers leveraging Playwright's native `page.route()` interception features to capture outgoing network signals, enabling seamless simulation of severe API failure modes (HTTP 500/503) and high latency without live database dependencies.
  * **Non-Standard Payload Handling:** Overrides anomalous system behaviors (like APIs returning HTTP 200 OK statuses during application-level core execution failures) by parsing deeply nested payload response dictionaries and asserting directly on internal payload data keys (`responseCode` and `message`).
  * **Parallel Execution Matrix:** Features parallel, headless multi-browser execution loops running concurrently across Chromium, Firefox, and WebKit (Safari), orchestrated fully via a unified `pytest.ini` setup configuration.

##### 🛒 [playwright-ecommerce-framework](https://github.com)
* **Application Under Test:** `saucedemo.com` (E-Commerce Web Core App)
* **Stack:** Python 3 • Playwright • PyTest • Parameterized Data Matrices • GitHub Actions
* **Deep Architecture Implementation:**
  * **Data-Driven Authentication:** Leverages specialized PyTest parameterized fixtures to dynamically inject varying structured test accounts, validating application state behaviors for valid profiles, locked-out credentials, and input formatting errors.
  * **Fixture Lifecycle Optimization:** Implemented reusable, custom-scoped PyTest fixtures to manage browser contexts efficiently, achieving robust execution isolation per test while decreasing browser instantiation overhead during high-concurrency parallel runs.

---

#### 📱 Mobile Test Automation Suites

##### 🤖 [hybrid_practice_appium](https://github.com)
* **Application Under Test:** General Store (Android Hybrid App Environment)
* **Stack:** Python 3 • Appium (UiAutomator2) • PyTest • Page Object Model • Allure Telemetry Dashboards
* **Deep Architecture Implementation:**
  * **Asynchronous Context Polling Engine:** Resolves timing race conditions when executing transitions from the device native OS layer into an embedded web container using a resilient recursive polling loop scanning `driver.contexts` every 1.5s (up to a 15-second timeout window).
  * **Fail-Safe Exception Triage:** Implemented a diagnostic execution hook within `pytest_runtest_makereport`. On unexpected test crashes, it hooks runtime failures, forces the driver context back to native, extracts a clean PNG device framebuffer screenshot, and embeds the telemetry directly inside the Allure Report.
  * **W3C Touch Action Chains:** Configured advanced physical touch gestures utilizing standard W3C ActionChains and `PointerInput` arrays to cleanly trigger complex 2.0-second long-press operations on deep UI overlay components.

##### ⚙️ [appium-native-regression](https://github.com)
* **Application Under Test:** `com.saucelabs.mydemoapp.rn` (React Native Production App)
* **Stack:** Python 3 • Appium (UiAutomator2) • PyTest • Coordinate Viewport Controls
* **Deep Architecture Implementation:**
  * **React Native Input Bypassing:** Overcomes UI freeze problems typical of React Native text field input masks by loop-injecting direct, low-level Android hardware keycodes (`driver.press_keycode(67)` for Backspace keys) to guarantee a pristine text array field before character injection loops start.
  * **Coordinate-Based Viewport Swipe Navigation:** Handles dynamic catalog structures rendering under the initial viewport fold line. Built an element index tracking loop that executes targeted vertical swipes (`driver.swipe(start_x=500, start_y=1800, end_x=500, end_y=800, duration=800)`) to cleanly navigate hidden tiles into active focus.
  * **Isolated Hermetic Runtime Binaries:** Configured using fully self-contained local workspace path parameters (`os.path.abspath("chromedriver")`) and isolated custom architecture binaries (`mac_arm64/v113`) directly inside the project root folder to guarantee a completely cross-platform, dependency-free deployment for other engineers.

---

### 📫 Let's Collaborate!

* 💼 **LinkedIn Profile:** [://linkedin.com](https://www.://linkedin.com-970351261/)
* 📧 **Corporate / Professional Email:** [pallawi20497@gmail.com](mailto:pallawi20497@gmail.com)
