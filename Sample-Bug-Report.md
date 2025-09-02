# 🐞 Sample Bug Report

This is a sample bug report format commonly used in SQA.  

---

## 🔹 Bug 1: Login Button Not Working

- **Bug ID**: BUG-001  
- **Module**: Login Page  
- **Severity**: High  
- **Priority**: Critical  
- **Steps to Reproduce**:  
  1. Go to Login Page  
  2. Enter valid username & password  
  3. Click Login button  
- **Expected Result**: User should be redirected to the Dashboard.  
- **Actual Result**: Nothing happens, page stays the same.  
- **Status**: Open  

---

## 🔹 Bug 2: Registration Email Validation Missing

- **Bug ID**: BUG-002  
- **Module**: Registration Page  
- **Severity**: Medium  
- **Priority**: High  
- **Steps to Reproduce**:  
  1. Open Registration Page  
  2. Enter invalid email format (`abc`)  
  3. Click Register  
- **Expected Result**: Validation error → "Enter a valid email"  
- **Actual Result**: User is registered with invalid email.  
- **Status**: Open  

---

## 🔹 Bug 3: Logout Redirects to Error Page

- **Bug ID**: BUG-003  
- **Module**: Logout Functionality  
- **Severity**: Low  
- **Priority**: Medium  
- **Steps to Reproduce**:  
  1. Login successfully  
  2. Click Logout button  
- **Expected Result**: Redirect to Login Page  
- **Actual Result**: Redirects to 404 error page  
- **Status**: Open  
