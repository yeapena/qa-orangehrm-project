# 📄 API Testing Report – Reqres API

## ✅ Tested Endpoints
- `GET /api/users?page=2` – Retrieve user list
- `POST /api/users` – Create a user
- `POST /api/login` – Negative test (Missing password)

## 🔧 Tools Used
- Postman
- JavaScript tests (assertions in Tests tab)

## 🔍 Scenarios
| Test Case                        | Expected Result                | Status |
|----------------------------------|--------------------------------|--------|
| Get All Users                    | 200 OK + non-empty user list   | ✅ Pass |
| Create User                      | 201 Created + ID returned      | ✅ Pass |
| Login – Missing Password         | 400 Bad Request + error message| ✅ Pass |

## 👩‍💻 Author
Yeanny Pena  
July 2025
