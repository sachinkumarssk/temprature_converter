# temprature_converter
# 🌡️ Temperature Converter with AI (Gemini API)

This is a **Temperature Converter Web App** built using **HTML, Tailwind CSS, and JavaScript**, with an additional **AI-powered feature** using **Google Gemini API**.  
It allows users to convert temperatures between **Celsius, Fahrenheit, and Kelvin**, and get **AI-generated insights** describing how that temperature might feel in real life with clothing suggestions.

---

## 🚀 Features
- 🔄 **Temperature Conversion** between Celsius (°C), Fahrenheit (°F), and Kelvin (K)  
- 🎨 **Modern UI** built with Tailwind CSS & Google Fonts  
- ✅ **Input Validation** with error messages  
- ⌨️ **Keyboard Support** – Press Enter to convert  
- 🤖 **Gemini AI Integration**:  
  - Describes what the given temperature feels like in relatable terms  
  - Suggests appropriate clothing  
- 🔁 **Retry with Exponential Backoff** in case API call fails  

---

## 🛠️ Tech Stack
- **HTML5** – Structure  
- **Tailwind CSS** – Styling with utility classes  
- **JavaScript (Vanilla)** – Conversion logic, API calls, error handling  
- **Google Gemini API** – AI-powered temperature description  

---

## 📂 Project Structure
📁 Temperature-Converter-AI
┣ 📜 index.html # Main application (HTML + Tailwind + JS)
┗ 📜 README.md # Documentation


---

## 🎮 Usage
1. Open `index.html` in any modern browser.  
2. Enter a **temperature value** and select the **unit (Celsius, Fahrenheit, Kelvin)**.  
3. Click **Convert** (or press `Enter`) to see converted results.  
4. After conversion, click **✨ What does this feel like?** to get AI-powered insights.  

---

## 🔑 API Setup
This app uses the **Google Gemini API**.  
- Replace the API key inside `index.html` at this line:
  ```js
  const apiKey = "YOUR_API_KEY_HERE";
