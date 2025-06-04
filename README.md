# 9am Solution – Backend API ( Express + MongoDB)

This is the backend API for the 9am Solution MERN stack application. It handles user authentication, shop management, and session handling using JWT and cookies.

---

## 🚀 Tech Stack

| Layer        | Tech                                      |
|--------------|-------------------------------------------|
| Runtime      | Node.js                                   |
| Framework    | Express.js                                |
| Database     | MongoDB (via Mongoose)                    |
| Auth         | JWT, HTTP-only cookies                    |
| Hosting      | Vercel (serverless functions)             |

---

##  Installation

### 1. Clone the repository

```
git clone https://github.com/rakib-gazi/9am-solution-server.git
cd 9am-solution-server
```
### 2. Install dependencies

```
npm install
```
### 3. Create a .env file
```
DB_USER = your database username
DB_PASSWORD =your database password
ACCESS_TOKEN_SECRET = your jwt secrect key
```
---
## Base URL
```
https://mern-server-nu.vercel.app
```
---
## API 

**1. Sign up (POST)**  
https://mern-server-nu.vercel.app/users

**2. Sign In (POST)**  
https://mern-server-nu.vercel.app/auth/signin

**3. Verify Token (POST)**  
https://mern-server-nu.vercel.app/auth/verify-token

**4. Sign Out (POST)**  
https://mern-server-nu.vercel.app/auth/signout


---
### 5. Folder structure
```
9am-solution-server/
├── index.js
├── package.json
├── .env.example
└── vercel.json
```
---
## Authentication
- Uses JWT for authentication.
- Tokens are stored in HTTP-only cookies for security.
- Session handling supports "Remember Me" functionality with different expiration times.
---
## Deployment
This project is configured for deployment on Vercel using serverless functions. The vercel.json file specifies the necessary settings.
---
## Thank You
