# 📑 Sample Test Cases

These are example test cases prepared as part of my QA learning journey.  

---

## 🔹 Login Module

| Test Case ID | Test Scenario           | Test Steps                                                                 | Test Data                | Expected Result                  | Status |
|--------------|-------------------------|----------------------------------------------------------------------------|--------------------------|----------------------------------|--------|
| TC-001       | Login with valid data   | 1. Open login page <br> 2. Enter valid username & password <br> 3. Click login | Username: user1 <br> Password: 12345 | User is logged in successfully | Pass   |
| TC-002       | Login with invalid password | 1. Open login page <br> 2. Enter valid username & invalid password <br> 3. Click login | Username: user1 <br> Password: wrong | Error message: "Invalid credentials" | Pass   |
| TC-003       | Login with empty fields | 1. Open login page <br> 2. Leave fields blank <br> 3. Click login button | Empty fields | Validation error message displayed | Pass   |

---

## 🔹 Registration Module

| Test Case ID | Test Scenario               | Test Steps                                                                 | Test Data               | Expected Result                | Status |
|--------------|-----------------------------|----------------------------------------------------------------------------|-------------------------|--------------------------------|--------|
| TC-004       | Register with valid data    | Fill all fields with valid inputs → Submit                                | Name: John <br> Email: john@test.com <br> Password: 12345 | User registered successfully | Pass |
| TC-005       | Register with missing email | Leave Email field empty → Submit                                           | Name: John <br> Email: - <br> Password: 12345 | Validation error for Email | Pass |
| TC-006       | Register with duplicate email | Enter already registered email → Submit                                   | Name: Alex <br> Email: john@test.com <br> Password: 67890 | Error message: "Email already exists" | Fail |
