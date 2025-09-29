# NodeJS Authentication System (LAB: Security in NodeJS)

## Student Info
**22687891_Dương Thị Thanh Thảo**

---

## How to run
```bash
npm install
npm start
```
MongoDB phải chạy trước (local).  
Ứng dụng chạy ở: [http://localhost:3000](http://localhost:3000)

---

## Endpoints & How to test (POSTMAN)

### Sign Up
POST `http://localhost:3000/user/signup`  
Body JSON: { "username": "bob", "email": "bob@example.com", "password": "12345", "cpassword": "12345" }  
![signup](public/results/signup.png)

### Sign In
POST `http://localhost:3000/user/signin`  
Body JSON: { "email": "bob@example.com", "password": "12345" }  
![signin](public/results/signin.png)

### Homepage
GET `http://localhost:3000/user/homepage`  
![homepage](public/results/homepage.png)

### Sign Out
GET `http://localhost:3000/user/signout`  
![signout](public/results/signout.png)

### Forgot Password
POST `http://localhost:3000/user/forgot-password`  
![forgot_password](public/results/forgot_password.png)

### Change Password
POST `http://localhost:3000/user/change-password`  
![change_password](public/results/change_password.png)

### Google Login
GET `http://localhost:3000/auth/google`  
![google_login](public/results/google_login.png)

---

## Screenshots
(Ảnh nằm trong `public/results/` đã commit)

---

## Commit & Push
```bash
git add .
git commit -m "NodeJS Authentication System - Added Student Info + Tested All Features"
git push origin main
```
