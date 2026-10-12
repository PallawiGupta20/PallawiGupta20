# Hi, I'm Pallawi Gupta 👋
### SDET & Automation Framework Architect

<p align="left">
  <a href="https://linkedin.com"><img src="https://shields.io" alt="LinkedIn" /></a>
  <a href="mailto:pallawi20497@gmail.com"><img src="https://shields.io" alt="Email" /></a>
  <img src="https://shields.io" alt="Experience" />
  <img src="https://shields.io" alt="Company" />
</p>

I am a Software Development Engineer in Test (SDET) and QA Automation Engineer with **3+ years of professional experience** at **MediaTek**. I specialize in building scalable, production-grade E2E automation frameworks and deep-dive **Hardware, OS, and API Performance Validation** workflows. My expertise extends beyond standard UI clicking to full-stack quality engineering: intercepting network traffic, analyzing system kernels, running hardware-level power diagnostics, and maintaining continuous delivery integration.

---

### 🛠️ Interactive Engineering Stack

*Click any tech badge to immediately explore my code repositories filtering for that specific ecosystem.*

<table>
  <tr>
    <td align="center" width="25%"><b>Layer / Vector</b></td>
    <td align="center" width="75%"><b>Interactive Technical Ecosystem Badges</b></td>
  </tr>
  <tr>
    <td align="center"><b>Web & UI Testing</b></td>
    <td>
      <a href="https://github.com"><img src="https://shields.io" /></a>
      <a href="https://github.com"><img src="https://shields.io" /></a>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Mobile Automation</b></td>
    <td>
      <a href="https://github.com"><img src="https://shields.io" /></a>
      <a href="https://github.com"><img src="https://shields.io" /></a>
    </td>
  </tr>
  <tr>
    <td align="center"><b>API Validation</b></td>
    <td>
      <a href="https://github.com"><img src="https://shields.io" /></a>
      <a href="https://github.com"><img src="https://shields.io" /></a>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Performance & Core</b></td>
    <td>
      <a href="https://github.com"><img src="https://shields.io" /></a>
      <a href="https://github.com"><img src="https://shields.io" /></a>
      <a href="https://github.com"><img src="https://shields.io" /></a>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Drivers & Logic</b></td>
    <td>
      <a href="https://github.com"><img src="https://shields.io" /></a>
      <a href="https://github.com"><img src="https://shields.io" /></a>
      <a href="https://github.com"><img src="https://shields.io" /></a>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Telemetry & BI</b></td>
    <td>
      <a href="https://github.com"><img src="https://shields.io" /></a>
      <a href="https://github.com"><img src="https://shields.io" /></a>
    </td>
  </tr>
</table>

---

### 📊 Master Test Automation Portfolio

<details open>
<summary><b>🌐 Web & API Testing Architectures (Click to Expand/Collapse)</b></summary>
<br>

##### 🧬 [playwright-api-ui-hybrid](https://github.com)
* **Application Under Test:** `automationexercise.com` (Public API & Web Platform)
* **Stack:** `Python 3` • `Playwright` • `PyTest` • `API Client Pattern` • `GitHub Actions`
* **Deep Architecture Implementation:**
  * **API-to-UI Cross-Validation Engine:** Maps asynchronous API Client patterns directly against modular UI Page Objects. Queries REST endpoints using Playwright, parses JSON schemas on the fly, and injects those data variables straight into the UI layer to cross-verify layout rendering fidelity and catch front-end data corruption bugs.
  * **Advanced Network Request Interception:** Built structural request mocking layers leveraging Playwright's native `page.route()` interception features to capture outgoing network signals, enabling seamless simulation of severe API failure modes (HTTP 500/503) and high latency without live database dependencies.
  * **Non-Standard Payload Handling:** Overrides anomalous system behaviors (like APIs returning HTTP 200 OK statuses during application-level core execution failures) by parsing deeply nested payload response dictionaries and asserting directly on internal payload data keys (`responseCode` and `message`).
  * **Parallel Execution Matrix:** Features parallel, headless multi-browser execution loops running concurrently across Chromium, Firefox, and WebKit (Safari), orchestrated fully via a unified `pytest.ini` setup configuration.

##### 🛒 [playwright-ecommerce-framework](https://github.com)
* **Application Under Test:** `saucedemo.com` (E-Commerce Web Core App)
* **Stack:** `Python 3` • `Playwright` • `PyTest` • `Parameterized Data Matrices` • `GitHub Actions`
* **Deep Architecture Implementation:**
  * **Data-Driven Authentication Matrix:** Leverages specialized PyTest parameterized fixtures to pass varying structured test data arrays into the authentication classes. This concurrently validates how the application UI handles clean system logins, input validation failures, and severe edge cases like globally locked-out user account profiles.
  * **Fixture Lifecycle Optimization:** Implemented reusable, custom-scoped PyTest fixtures to manage browser contexts efficiently, achieving robust execution isolation per test while decreasing browser instantiation overhead during high-concurrency parallel runs.

##### 📡 [rest-api-automation-postman](https://github.com) *(Framework Core)*
* **Ecosystem Highlight:** `Postman` • `Newman CLI` • `CI/CD Execution`
* **Deep Architecture Implementation:** Collection designs executing complex HTTP request chains (`GET`, `POST`, `PUT`, `DELETE`). Implemented fully parameterized global environment configurations, dynamic test assertion scripts validating contract compliance, schema shapes, and response structures, backed by `Newman` execution pipelines for headless terminal test runner deployments.

</details>

<br>

<details open>
<summary><b>📱 Mobile Test Automation & Hardware Performance (Click to Expand/Collapse)</b></summary>
<br>

##### 🤖 [hybrid_practice_appium](https://github.com)
* **Application Under Test:** General Store (Android Hybrid App Environment)
* **Stack:** `Python 3` • `Appium (UiAutomator2)` • `PyTest` • `Page Object Model` • `Allure Telemetry Dashboards`
* **Deep Architecture Implementation:**
  * **Asynchronous Context Polling Engine:** Resolves timing race conditions when executing transitions from the device native OS layer into an embedded web container using a resilient recursive polling loop scanning `driver.contexts` every 1.5s (up to a 15-second timeout window).
  * **Fail-Safe Exception Triage:** Implemented a diagnostic execution hook within `pytest_runtest_makereport`. On unexpected test crashes, it hooks runtime failures, forces the driver context back to native, extracts a clean PNG device framebuffer screenshot, and embeds the telemetry directly inside the Allure Report.
  * **W3C Touch Action Chains:** Configured advanced physical touch gestures utilizing standard W3C ActionChains and `PointerInput` arrays to cleanly trigger complex 2.0-second long-press operations on deep UI overlay components.

##### ⚙️ [appium-native-regression](https://github.com)
* **Application Under Test:** `com.saucelabs.mydemoapp.rn` (React Native Production App)
* **Stack:** `Python 3` • `Appium (UiAutomator2)` • `PyTest` • `Android ADB Keycodes`
* **Deep Architecture Implementation:**
  * **React Native Input Bypassing:** Overcomes UI freeze problems typical of React Native text field input masks by loop-injecting direct, low-level Android hardware keycodes (`driver.press_keycode(67)` for Backspace keys) to guarantee a pristine text array field before character injection loops start.
  * **Coordinate-Based Viewport Swipe Navigation:** Handles dynamic catalog structures rendering under the initial viewport fold line. Built an element index tracking loop that executes targeted vertical swipes (`driver.swipe(start_x=500, start_y=1800, end_x=500, end_y=800, duration=800)`) to cleanly navigate hidden tiles into active focus.

##### 🏎️ [android-performance-validation](https://github.com) *(OS & Hardware Performance Core)*
* **Ecosystem Highlight:** `Perfetto` • `Systrace` • `Low Power Monsoon Hardware` • `Android ADB & Monkey`
* **Deep Architecture Implementation:**
