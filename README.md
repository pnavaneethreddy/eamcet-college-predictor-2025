# 🎓 EAMCET College Predictor

A web application that helps students predict colleges they may get into based on their EAMCET rank, category, gender, and preferred branch.

## 🌐 Live Demo

[View Live][(https://pnavaneethreddy.github.io/eamcet-college-predictor-2025/)]

---



## 🚀 Features

* Predicts colleges based on:

  * EAMCET rank
  * Category & gender
  * Engineering branch
* Displays cutoff ranks from multiple counseling phases
* Clean, mobile-responsive UI
* Animated transitions using AOS
* Fast API built with Node.js and Express
* Connected to a MongoDB database

---

## ⚙️ Tech Stack

**Frontend**:

* HTML, CSS, JavaScript
* AOS (Animate On Scroll)
* Font Awesome

**Backend**:

* Node.js, Express.js
* MongoDB, Mongoose

**Deployment**:

* Github (frontend & serverless API)

---

## ⚙️ Setup Locally

```bash
# Clone the repo
git clone https://github.com/your-username/eamcet-college-predictor.git
cd eamcet-college-predictor

# Install dependencies
npm install

# Create .env file
touch .env
```

Add your MongoDB credentials in `.env`:

```env
MONGO_URI=mongodb+srv://your-db-uri
DB_NAME=Eamcet_Cleaned_data
PORT=5000
```

```bash
# Run the server
npm start
```

---

## 📂 Folder Structure

```
├── index.html        # Frontend UI
├── server.js         # Express API
├── .env              # Environment variables
├── vercel.json       # Vercel routing
├── package.json      # Node metadata
```

---

## 👨‍💻 Author

**Navaneeth Reddy Peddireddy**
[Instagram](https://www.instagram.com/navaneethreddypeddireddy/)
[LinkedIn](https://www.linkedin.com/in/navaneeth-reddy-peddireddy-382a14302/)

---

## 📄 License

This project is licensed under the MIT License.
