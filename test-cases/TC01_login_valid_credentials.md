# ✅ Test Case: TC01 – Login with Valid Credentials

## 🔹 Objective:
Verify that a user can successfully log in with valid credentials.

---

## 🧾 Preconditions:
- User is on the OrangeHRM login page
- Valid credentials:  
  Username: `Admin`  
  Password: `admin123`

---

## 🧪 Test Steps:

| Step | Action                                     | Expected Result                            |
|------|--------------------------------------------|---------------------------------------------|
| 1    | Navigate to [https://opensource-demo.orangehrmlive.com/](https://opensource-demo.orangehrmlive.com/) | Login page is displayed                    |
| 2    | Enter username `Admin`                     | Username field accepts input                |
| 3    | Enter password `admin123`                  | Password field accepts input                |
| 4    | Click the "Login" button                   | User is logged in and dashboard appears     |

---

## ✅ Expected Result:
- User is redirected to the admin dashboard (URL contains `/dashboard`)
- No error messages are shown

## 🛠️ Test Data:
- Username: `Admin`
- Password: `admin123`

## 📌 Status:
- Pass ✅ / Fail ❌ _(update after testing)_

## 📅 Author:
Yeanny Pena
