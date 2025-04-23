# Medical Portal
##  Description
The **Medical Portal System** is a web application designed for clinical environments to help manage patient data securely and efficiently. The system uses **JWT authentication**, **bcrypt password hashing**, and **role-based access** to control who can view and update patient information.

## role
- Admin
- Doctor
- Patient

  ## Tech Stack

###  Backend
- **Node.js**
- **Express.js**
- **MongoDB**
- **bcrypt**
- **jsonwebtoken (JWT)**
- **formidable** (for form handling)
- **dotenv** (for environment variables)
- **cors** (to enable frontend-backend communication)

###  Frontend
- **React**
- **JavaScript**
- **Axios** (assumed for API calls)
- **React Router DOM**

---
## Features

-  JWT-based login for secure sessions
-  Role-based access control for doctors and admins
-  Admin features:
  - Register new doctors and patients
  - Edit patient  and doctor contact details
-  Doctor features:
  - View patient data
  - **Add medical records after patient checkup**
-  No patient login or access
-  Secure password storage using bcrypt

---

## 🛠 Setup Instructions

### 1. Clone the Repository

### 2.  Backend setup
```bash
cd backend
npm install
npm run start

```
### 3. Frontend setup
```bash
cd frontend
npm install
npm run dev


