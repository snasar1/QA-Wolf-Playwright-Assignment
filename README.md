# QA Wolf Assignment: Hacker News Article Validation

## **Overview**
This project automates the validation of articles on the Hacker News "Newest" page, ensuring they are sorted correctly from newest to oldest. It uses [Playwright](https://playwright.dev/) for browser automation and Node.js to execute the script.

---

## **Features**
- **Automated Browser Interaction:** Launches a Chromium browser and navigates to the Hacker News "Newest" page.
- **Article Extraction:** Scrapes the first 100 articles, capturing their titles and post times.
- **Sorting Validation:** Checks if the articles are correctly sorted from newest to oldest.
- **Error Handling:** Provides meaningful error messages in case of sorting issues.
- **Screenshot Capture:** Saves a screenshot of the page for additional validation.

---

## **Technologies Used**
- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [Playwright](https://playwright.dev/) (Browser automation library)

---

## **Getting Started**

### **Prerequisites**
- [Node.js](https://nodejs.org/) installed on your system.
- Basic knowledge of JavaScript and Node.js environment.

### **Installation**

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
