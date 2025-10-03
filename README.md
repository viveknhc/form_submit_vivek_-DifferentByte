# Demo Form Submission (Static HTML + jQuery)

This project demonstrates how to submit a form using **AJAX (POST)** with a **demo CSRF token** for security simulation.  
Since this is a **static HTML project**, no real API or database is connected.  

---

## 📌 Features
- Static HTML form with fields: `name`, `email`, `message`.
- Form submission handled via **jQuery AJAX**.
- **CSRF token** included in request headers for demo security.
- Uses a **fake endpoint** (`/form/`) with method `POST` to simulate data submission.
- No backend or real database is involved.

---

## ⚠️ Important Notes
1. **No API is added**  
   This is a front-end demo only. There is no real server or backend to handle form data.

2. **Demo CSRF Token**  
   Instead of generating a real CSRF token from a server, a static token (`demo-csrf-token`) is used just to demonstrate how tokens are normally passed in AJAX headers.

3. **POST Endpoint (Simulation)**  
   - The form submits via `POST` to a demo endpoint (`/form/`).  
   - Since there is no backend, this request will not return real data.  
   - In a real project, this endpoint should be replaced with your actual API or backend route.

---

## 🚀 How to Run
1. Download or clone this repository.
2. Open `index.html` in your browser.
3. Fill out the form and click **Submit**.
4. Check your browser **console** (`F12 → Console`) to see simulated responses.

---

## 📂 File Structure
