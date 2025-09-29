## 🔐 Login & Register Page – Level 5 Authentication(Environment Variables + Session-Based Authentication) #

This project is a Login & Register Authentication System built with Node.js, Express, EJS, and PostgreSQL.
It demonstrates Level 5 Authentication, where:

User passwords are hashed and salted using bcrypt.js.

Session-based authentication is implemented with cookies using express-session.

Database credentials and session secrets are stored in environment variables (.env) for security.

Users can register with an email and password, log in securely, and access a protected secrets page.
The project uses a modular EJS structure with partials (header.ejs, footer.ejs) and serves static assets through the public folder.

---
🔑 Levels of Authentication:<br><br>
Level 1: Basic Cipher (Caesar, Hill, Playfair, etc.)<br>
Level 2: Hashing (MD5, SHA, etc.)<br>
Level 3: Hashing + Salt Rounds (bcrypt)<br>
Level 4: Session-Based Authentication (bcrypt + Passport.js + Cookies)<br>
Level 5: Environment Variables + Session-Based Authentication<br>
Level 6: OAuth (Open Authorization) 



---
📂 Project Structure:<br><br>
Authentication Lv.5<br>
├── .DS_Store<br>
├── .gitignore<br>
├── ENV.txt<br>
├── css<br>
    └── styles.css<br>
├── index.js<br>
├── package-lock.json<br>
├── package.json<br>
├── partials<br>
    ├── footer.ejs<br>
    └── header.ejs<br>
├── public<br>
    └── css<br>
    │   └── styles.css<br>
└── views<br>
    ├── home.ejs<br>
    ├── login.ejs<br>
    ├── partials<br>
        ├── footer.ejs<br>
        └── header.ejs<br>
    ├── register.ejs<br>
    └── secrets.ejs<br>


---

## 📷 Gallery

| SignUp Page | Login Page |
|-------------|------------|
| ![lgl1](./imgg/lgl1.png) | ![a3](./imgg/a3.png) |

| Register Page | Secret Page |
|---------------|-------------|
| ![al1](./imgg/al1.png) | ![alia](./imgg/alia.png) |



---

## ⚙️ Setup Instructions

 1️⃣ Create Table in PostgreSQL(users):
 <br><br>
    as given in the query.sql
 <br>
 
2️⃣ Install Dependencies:
```bash
npm i
npm i pg express ejs body-parser
```

4️⃣ Edit .env file:<br><br>
    as give in the .ENV.txt
<br>
5️⃣ Run Server: 
```bash
node index.js
```
---
👉 [Open App on Localhost](http://localhost:3000)
