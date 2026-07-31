<h1 align="center">Hi 👋, I'm Nimra Saeed</h1>
<h3 align="center">QA Automation Engineer | Manual & API Testing</h3>

<p align="center">I build reliable automation frameworks and data-driven testing pipelines, combining manual and automation testing — from UI and API validation to SQL-based database checks across web and mobile applications.</p>

<p align="center">
  <a href="https://github.com/NimraSaeed567">
    <img src="https://komarev.com/ghpvc/?username=NimraSaeed567&label=Profile%20Views&color=grey&style=flat" alt="Nimra Saeed profile views"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nimra-saeed-aaa55a2b7/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:engr.nimrasaeed567@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://nimra-saeed.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=netlify&logoColor=white" /></a>
</p>

---

### 👩‍💻 About Me

My work spans:

- 🎓 **Electrical Engineering** background (NUST) applied to a systematic, data-first approach to software quality
- 🧪 **Manual & automation testing** — functional, regression, sanity, smoke, integration, system, CRUD, and exploratory testing
- 🔧 **Automation frameworks** built with **Selenium**, **Playwright**, and **Cypress** across web and mobile applications
- 🔌 **API testing** with Postman — request/response validation, status codes, error handling, and CI/CD integration
- 🗄️ **Database & backend validation** using SQL — defect trends, module-wise failure rates, and test coverage metrics
- 🔁 **Agile/Scrum** — sprint planning, backlog grooming, Boundary Value Analysis, and shift-left testing practices

I currently work as an **SQA Engineer at Allshore Talent**, executing end-to-end, functional, regression, and exploratory testing across web and mobile applications, plus backend validation via SQL.

---

### 💼 Professional Experience

**🔹 SQA Engineer — Allshore Talent** — *Remote Islamabad, Pakistan* &nbsp;|&nbsp; Mar 2026 – Present
- Execute end-to-end, functional, regression, sanity, smoke, integration, system, CRUD, and exploratory testing on web and mobile applications to identify defects and ensure a smooth user experience
- Create and maintain detailed test cases, test scenarios, and test data from business requirements and user stories, and track defects to closure with developers and product teams
- Execute SQL queries for backend data validation and database testing, and perform UI/UX, cross-browser, cross-platform, accessibility, and localization testing across devices and browsers

**🔹 QA Analyst — Hypertext Solutions** — *Islamabad, Pakistan* &nbsp;|&nbsp; Dec 2025 – Mar 2026
- Designed and executed manual functional, regression, smoke, and sanity test cases for web applications, logging and tracking defects through resolution in JIRA
- Performed API testing with Postman to validate request/response payloads, status codes, and error handling across backend endpoints
- Ran SQL queries for backend data validation and test data setup, and worked with developers and product owners in Agile sprints, contributing to sprint planning, standups, and release readiness reviews

**🔹 SQA Engineer — Octathorn (NASTP)** — *Rawalpindi, Pakistan* &nbsp;|&nbsp; Jul 2025 – Nov 2025
- Performed manual, automation, and API testing on web and mobile applications using Playwright and TestNG, designing and executing automated test scripts to improve test efficiency and coverage
- Performed database validation using SQL queries to verify application data, identify inconsistencies, and support defect investigation and root cause analysis
- Collaborated with cross-functional teams to define test strategies, create test cases, and validate requirements for reliable releases

**🔹 QA Intern — Emumba Private Limited** — *Islamabad, Pakistan* &nbsp;|&nbsp; Jun 2024 – Aug 2024
- Conducted manual, functional, and regression testing, along with API testing using Postman, ensuring software quality through test case design, defect logging, and test execution with tools like JIRA and Selenium
- Developed and implemented UI automation frameworks using Selenium, Cucumber, and JUnit, applying Java-based testing, bug lifecycle understanding, test planning, and root cause analysis
- Executed SQL queries for database validation and backend testing, and participated in defect triaging, root cause analysis, and test planning with development teams

---

### 🚀 Featured Projects

#### 🧪 SwagLabs UI Automation
**Technologies:** Playwright, TypeScript, Page Object Model

- Page Object Model suite for Swag Labs — Login, Logout, Inventory, Cart, and Checkout pages
- Custom Playwright fixtures inject page objects and a pre-authenticated session
- Custom reporter auto-generates a Markdown bug report per failing test — repro steps, expected vs. actual, and links to screenshot/video/trace
- Runs across Chromium, Firefox, and WebKit, with a per-run `test-summary.md`

#### ☕ SauceDemo Java Automation
**Technologies:** Selenium, JUnit 5, Java

- 7 end-to-end test cases: login, cart add/remove (from Products, Checkout, and Product Details pages), full purchase flow, cart persistence across logout/login, and all 4 sort options verified against actual expected order
- Custom HTML reporter logging pass/fail status per test step
- Credentials loaded from an external JSON config via Jackson's `ObjectMapper`
- Runs against a remote Selenium Grid

#### 🏥 Healthcare Telehealth QA Automation
**Technologies:** Playwright

- E2E tests for a telehealth platform: admin user/facility/organization management, dashboard team & weekly-schedule management, knowledge-base topic management, and login
- Cross-browser verification across Chromium, WebKit, and Firefox
- Responsive layout testing across mobile, tablet, and desktop viewports for booking workflows

#### 🧑‍💼 OrangeHRM Automation
**Technologies:** Cypress, Page Object Model

- Page Object Model suite: LoginPage, SidebarPage, AdminUserPage, PimPage, LeavePage
- Covers login validation, Admin > User Management (search/create/delete), PIM > Employee List (search/create/delete), and Leave navigation
- Login cached per test run via `cy.session`; data-creating tests clean up after themselves since this runs against a shared public demo instance

#### ☀️ Weather Shopper Automation
**Technologies:** Cucumber, Selenium, Java, ExtentReports

- BDD feature file drives a full purchase journey: check temperature → buy moisturizer or sunscreen based on it → add to cart → checkout → complete payment
- Page Object Model: HomePage, MoisturizersPage, SunscreensPage, CartPage, CheckoutPage
- ExtentReports HTML reporting per run

#### 📊 CRM Dashboard
**Technologies:** React 19, Vite, Tailwind CSS, Supabase, Recharts

- KPI dashboard with revenue, pipeline, and lead-source charts, plus customer/task/invoice managers
- **Ask AI** — natural-language querying over dashboard data via a Vercel serverless function calling OpenRouter, keeping the API key server-side only
- Supabase-backed auth and Postgres database, light/dark theme support

#### 🩸 AI-Driven Leukemia Detection (FYP, FPGA)
**Technologies:** Python, Keras, OpenCV

- Final year project — processes the C-NMC Leukemia microscopy image dataset
- Extracts image-derived signal features (flattened + FFT-based frequency-domain features) as a bridge toward FPGA-based signal processing
- Trains a Dense/Dropout Keras neural network, evaluated via confusion matrix and classification report
- Reported result: **MobileNetV2, 96% test accuracy**

More on my [portfolio site →](https://nimra-saeed.netlify.app/)

---

### 🛠️ Technical Skills

**Languages & Databases**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white)
![C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Automation & API Tools**

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=flat-square&logo=cucumber&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-E34F26?style=flat-square)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![JMeter](https://img.shields.io/badge/JMeter-D22128?style=flat-square&logo=apachejmeter&logoColor=white)

**Testing Types**

![Functional](https://img.shields.io/badge/-Functional%20Testing-blue?style=flat-square)
![Regression](https://img.shields.io/badge/-Regression%20Testing-blue?style=flat-square)
![Smoke](https://img.shields.io/badge/-Smoke%20Testing-blue?style=flat-square)
![Sanity](https://img.shields.io/badge/-Sanity%20Testing-blue?style=flat-square)
![Integration](https://img.shields.io/badge/-Integration%20Testing-blue?style=flat-square)
![Exploratory](https://img.shields.io/badge/-Exploratory%20Testing-blue?style=flat-square)
![UAT](https://img.shields.io/badge/-User%20Acceptance%20Testing-blue?style=flat-square)
![Performance](https://img.shields.io/badge/-Performance%20Testing-blue?style=flat-square)
![Security](https://img.shields.io/badge/-Security%20Testing-blue?style=flat-square)
![Risk-Based](https://img.shields.io/badge/-Risk--Based%20Testing-blue?style=flat-square)

**QA Process, Test Design & Tools**

![Agile](https://img.shields.io/badge/Agile-0052CC?style=flat-square)
![SDLC/STLC](https://img.shields.io/badge/-SDLC%2FSTLC-0052CC?style=flat-square)
![RTM](https://img.shields.io/badge/-Traceability%20Matrix-0052CC?style=flat-square)
![BVA](https://img.shields.io/badge/-Boundary%20Value%20Analysis-0052CC?style=flat-square)
![Equivalence Partitioning](https://img.shields.io/badge/-Equivalence%20Partitioning-0052CC?style=flat-square)
![Decision Table](https://img.shields.io/badge/-Decision%20Table%20Testing-0052CC?style=flat-square)
![Pairwise](https://img.shields.io/badge/-Pairwise%20Testing-0052CC?style=flat-square)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)

---

### 🎓 Education

**Bachelor of Engineering in Electrical Engineering (BE)**
NUST College of Electrical and Mechanical Engineering, Rawalpindi, Pakistan
*2021 – 2025*

---

### 📜 Certifications

- **Selenium 4 in Java**
- **JUnit 5**
- **Browser Automation using JavaScript**
- **SQL for Data Analysis**
- **Machine Learning with Python**

---

### 🤝 Open to Opportunities

I'm interested in roles and collaborations involving:

- Manual & automation testing (Selenium, Playwright, Cypress)
- API testing & backend validation (Postman, SQL)
- Test framework design and CI/CD integration
- QA process improvement, defect analysis, and release-readiness reporting

---

### 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NimraSaeed567&show_icons=true&theme=default&hide_border=true&count_private=true" height="165" alt="Nimra's GitHub stats" />
  <img src="https://streak-stats.demolab.com?user=NimraSaeed567&theme=default&hide_border=true" height="165" alt="Nimra's GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NimraSaeed567&layout=compact&theme=default&hide_border=true&langs_count=8" height="165" alt="Nimra's most used languages" />
</p>

---

### 📈 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=NimraSaeed567&theme=minimal&hide_border=true" alt="Nimra's GitHub contribution activity graph" />
</p>

---

### 📫 Let's Connect

<p align="center">
  <a href="mailto:engr.nimrasaeed567@gmail.com">
    <img src="https://img.shields.io/badge/Email-engr.nimrasaeed567%40gmail.com-D14836?style=for-the-badge&logo=gmail" alt="Email"/>
  </a>
  <a href="https://www.linkedin.com/in/nimra-saeed-aaa55a2b7/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect%20with%20me-0077B5?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
  <a href="https://nimra-saeed.netlify.app/">
    <img src="https://img.shields.io/badge/Portfolio-Visit%20site-000000?style=for-the-badge&logo=netlify" alt="Portfolio"/>
  </a>
</p>

<h3 align="center">🎯 Quality isn't a phase — it's a mindset 🎯</h3>

---

<p align="center"><sub>Last updated: this profile README is maintained alongside my pinned repositories above.</sub></p>
