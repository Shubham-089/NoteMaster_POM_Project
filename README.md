# 📝 Note Master Project (POM) | Selenium / Java / TestNG

This project is an end-to-end automation testing suite for the Note Master web app using Selenium WebDriver and Java, following the Page Object Model (POM) design.

## 🚀 Features

- Automated user signup with dynamic email generation using Apache Commons library.  
- Login validation with assertions using TestNG and Selenium.  
- Create Notes with title/body and Save functionality testing.  
- Add To-Do task with date selection and priority using dropdowns.  
- Logout functionality tested through profile interactions.  
- POM-based reusable page structure for clean and maintainable code.  
- Used assertion validations and thread waits for synchronization.  

## 🛠️ Tech Stack

- Language: Java  
- Automation: Selenium WebDriver  
- Framework: TestNG  
- Design Pattern: Page Object Model (POM)  
- Tools: ChromeDriver, Apache Commons Lang3  
- IDE: IntelliJ IDEA / Eclipse  
- Reporting: (Can be extended with Extent Reports)

## 📂 Project Structure

- `PageObjects/` – Contains all POM classes (LoginPage, SignupPage, DashBoard, NotesPage, ToDoPage, etc.)  
- `TestCase/UserFlow.java` – Contains complete test scenario for Signup, Login, Create Note, Add To-Do, Logout  
- `TestBase/BaseClass.java` – WebDriver setup and teardown logic  
- `README.md` – Project overview and documentation

## ✅ How to Run

1. Clone this repo: `git clone https://github.com/your-username/note-master-automation.git`  
2. Open in your preferred IDE (IntelliJ/Eclipse).  
3. Ensure ChromeDriver is in system PATH or project root.  
4. Run `UserFlow.java` as a TestNG test class.  

## 📌 Notes

- Used `Thread.sleep()` for simple waits; can be improved with explicit waits.  
- Uses random string generator to avoid email duplication.  
- Covers real-time user journey: Signup → Login → Add Notes → Add ToDo → Logout  

## 👤 Author

**Shubham Yetonde**  
Manual & Automation Tester | Selenium | Java | TestNG | Postman  
[LinkedIn](https://www.linkedin.com/in/shubham-yetonde-s27/) • [GitHub]([(https://github.com/Shubham-089))

---

