# 🧪 SoloLearn Web Test Automation Suite

![Selenium](https://img.shields.io/badge/Selenium_IDE-43B02A?style=for-the-badge&logo=Selenium&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=JUnit5&logoColor=white)
![Chrome](https://img.shields.io/badge/Google_Chrome-4285F4?style=for-the-badge&logo=Google-Chrome&logoColor=white)

An automated web testing portfolio project developed as part of **EEI5467: Software Testing and Quality Assurance** at **The Open University of Sri Lanka**. This suite validates the functionality, usability, and user workflows of the **SoloLearn** web platform using Selenium IDE and Java JUnit scripts.

---

## 📌 Features & Highlights

* **Comprehensive Test Coverage:** Functional testing across authentication, course catalog navigation, interactive quizzes, and community search.
* **Positive & Negative Validation:** Validates expected successful user journeys as well as error-handling behaviors (e.g., invalid login attempts).
* **Dual Execution Modes:** Ready to run natively via **Selenium IDE** (`.side` project) or programmatically via **Java JUnit** test suites.
* **Sanitized & Privacy-Safe:** All sensitive personal data, credentials, and identifiers have been sanitized with dummy test data.

---

## 🛠️ Tech Stack & Tools

* **Automation Tool:** Selenium IDE (Chrome Extension)
* **Scripting / Export:** Java (JUnit Framework)
* **Target Application:** [SoloLearn Web Platform](https://www.sololearn.com/)
* **Browser:** Google Chrome

---

## 📁 Repository Structure

```text
.
├── .selenium-project/
│   └── SoloLearn.side               # Main Selenium IDE project file
├── src/
│   ├── INVALIDloginTest.java        # Negative authentication test case
│   ├── VALIDloginTest.java          # Positive authentication test case
│   ├── NavigationTest.java          # Navigation bar routing verification
│   ├── CoursesTest.java             # Course catalog interaction tests
│   ├── QuizzTest.java               # Interactive quiz response validation
│   └── SearchTest.java              # Discussion board keyword search tests
├── docs/
│   └── TEST_DOCUMENTATION.pdf       # Full QA test case specifications report
└── README.md                        # Project documentation

```

---

## 📋 Test Suite Breakdown

| Test ID | Test Name | Description | Type |
| --- | --- | --- | --- |
| **TC-01** | `01_INVALID login` | Verifies system error alert when entering unregistered credentials. | Negative |
| **TC-02** | `02_VALID login` | Validates successful authentication and dashboard redirection. | Positive |
| **TC-03** | `03_navigation` | Verifies header navigation links (Leaderboard, Code Bits, Discuss, Blog). | Functional |
| **TC-04** | `04_Courses` | Validates browsing full course catalogs and selecting learning tracks. | Functional |
| **TC-05** | `05_Quizz` | Evaluates quiz option selection, answer checking, and score feedback. | Functional |
| **TC-06** | `06_search` | Tests keyword query execution (`"python basics"`) in discussion forums. | Functional |

---

## 🚀 How to Run the Tests

### Option 1: Executing via Selenium IDE (Chrome Extension)

1. Install the **Selenium IDE** browser extension for Google Chrome.
2. Launch Selenium IDE and choose **"Open an existing project"**.
3. Select `SoloLearn.side` from the `.selenium-project/` folder.
4. Click **"Run all tests"** to execute the automation suite live in your browser.

### Option 2: Running Programmatically via Java JUnit

1. Clone this repository to your local workspace:
```bash
git clone [https://github.com/](https://github.com/)<your-username>/sololearn-selenium-automation.git

```


2. Open the project in your preferred Java IDE (IntelliJ IDEA, Eclipse, or VS Code).
3. Ensure **Selenium WebDriver**, **ChromeDriver**, and **JUnit** are configured in your project dependencies.
4. Run individual test classes inside the `src/` directory directly as JUnit tests.

---

## 📄 Test Documentation

For detailed step-by-step test procedures, preconditions, expected vs. actual outcomes, and testing summary reports, refer to the document in `docs/TEST_DOCUMENTATION.pdf`.

---

*Developed for academic coursework in Software Testing & Quality Assurance at The Open University of Sri Lanka.*

```

```
