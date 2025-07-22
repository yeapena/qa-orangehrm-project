# 🧪 QA Test Plan – OrangeHRM Demo

## 1. Overview
This test plan outlines the QA strategy for validating core features of the OrangeHRM open-source demo application.

## 2. Objectives
- Verify login functionality and employee management features
- Identify and report any functional/UI bugs
- Test the API endpoints (where applicable)
- Automate key workflows using Selenium

## 3. Scope

### ✅ In Scope:
- Login and logout
- Add, edit, delete employee
- Search directory
- Basic UI layout and responsiveness

### ❌ Out of Scope:
- Mobile app testing
- Integration with external systems
- Performance/load testing

## 4. Test Types
- Functional Testing
- UI Testing
- API Testing (with Postman)
- UI Automation (with Selenium)

## 5. Tools
- GitHub (documentation)
- Postman (API testing)
- Selenium (UI automation, Python or Java)
- Chrome DevTools (console/log inspection)

## 6. Environment
- Application under test: [https://opensource-demo.orangehrmlive.com/](https://opensource-demo.orangehrmlive.com/)
- Browser: Chrome (latest)

## 7. Test Scenarios (Summary)
| ID  | Scenario                         | Priority |
|-----|----------------------------------|----------|
| TC01| Login with valid credentials     | High     |
| TC02| Login with invalid credentials   | High     |
| TC03| Add a new employee               | High     |
| TC04| Search for an employee           | Medium   |
| TC05| Logout from system               | High     |

## 8. Risks
- App is a demo site and may reset or behave inconsistently
- No backend access to test database state
- APIs may be limited or undocumented

## 9. Reporting
- Bugs will be documented in `/bug-reports/` as Markdown files
- API results will be saved as Postman collections
- Selenium scripts will be shared in `/selenium-tests/`

## 10. Author
Yeanny Pena
July 2025
