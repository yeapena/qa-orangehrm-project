# ❌ Test Case: TC02 – Login with Invalid Credentials

## 🔹 Objective:
Verify that the system prevents access when invalid credentials are used.

---

## 🧾 Preconditions:
- User is on the OrangeHRM login page
- Application is accessible
- Credentials used are **intentionally incorrect**

---

## 🧪 Test Steps:

| Step | Action                                     | Expected Result                                   |
|------|--------------------------------------------|----------------------------------------------------|
| 1    | Navigate to [https://opensource-demo.orangehrmlive.com/](https://opensource-demo.orangehrmlive.com/) | Login page is displayed                           |
| 2    | Enter username `wrongUser`                 | Username field accepts input                      |
| 3    | Enter password `wrongPass123`              | Password field accepts input                      |
| 4    | Click the "Login" button                   | An error message is displayed (e.g., "Invalid credentials") |

---

## ✅ Expected Result:
- Login fails
- User stays on the login page
- Error message appears, such as:  
  `"Invalid credentials"`

---

## 🛠️ Test Data:
- Username: `wrongUser`
- Password: `wrongPass123`

---

## 📌 Status:
- Pass ✅ 
<img width="549" height="255" alt="image" src="https://github.com/user-attachments/assets/c7dcc5f1-719a-428a-8aca-84fa66e96478" />

---

## 📅 Author:
Yeanny Pena
