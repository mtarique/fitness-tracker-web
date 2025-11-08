# 🏋️‍♂️ Fitness & Health Tracking App

A simple and responsive **Fitness Tracking Web App** built with **Bootstrap 5**, **HTML**, **CSS**, and **JavaScript**.  
It helps users calculate their **Body Mass Index (BMI)** instantly, view their **health category**, and get **AI-powered health tips** via Google’s AI search integration.

---

## 🚀 Live Demo
👉 [Live Preview](#) _(add your deployed link here)_

---

## 🧠 Features

- ⚡ **Instant BMI Calculation** — Enter your age, weight, and height to calculate BMI in real-time.  
- 📊 **Automatic BMI Classification** — Displays BMI category: *Underweight, Normal, Overweight,* or *Obese*.  
- 💡 **Smart Health Tips** — Dynamically generates a Google AI / Gemini / Search URL for personalized health guidance.  
- 🧾 **Simple & Clean UI** — Fully responsive layout built with **Bootstrap 5**.  
- 🧍 **User-Friendly Form** — Minimal inputs, instant results, and interactive guidance.  
- 🔗 **Open Source** — Easy to customize and extend for your own fitness-based project.

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | **HTML5**, **CSS3**, **Bootstrap 5** |
| Logic / Interactivity | **Vanilla JavaScript (ES6)**, **jQuery (optional)** |
| Integration | Google Search / AI Studio URL prompt |
| Hosting (optional) | GitHub Pages / Vercel / Netlify |

---

## 🧮 How It Works

1. User enters:
   - **Age**
   - **Weight (kg)**
   - **Height (cm)**
2. The app calculates:
   \[
   \text{BMI} = \frac{\text{Weight}}{(\text{Height in meters})^2}
   \]
3. Based on the result, it classifies into:
   - `< 18.5` → Underweight  
   - `18.5 - 24.9` → Normal weight  
   - `25 - 29.9` → Overweight  
   - `≥ 30` → Obese  
4. The app displays:
   - BMI value  
   - Health category  
   - Button: “Get AI Health Tips”  
5. Clicking the button opens a **Google AI / Search page** with a prefilled prompt like:  