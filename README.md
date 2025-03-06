# NinjaRMM_Automation

### Hi, 👋  
I HOPE YOU WILL READ THIS.  
I BELIEVE I HAVE COVERED **ALMOST ALL POSSIBLE LOGIN SCENARIOS**.  

❌ **Some tests are failing** due to **MFA (Multi-Factor Authentication)**.  
- When I **log in manually**, I can **pass MFA**.  
- When I **run automation**, it **asks for the MFA key**.  
- **Because of this, some tests fail**, and I couldn't fix them in this short time.  

---

## 📌 Project Structure
- **`login.test.js`** → **Long script** with **repetitive** code.  
- **`testScript.js`** → **Optimized version** using **reusable methods & classes**.  
- **`login.feature`** → Contains all **test scenarios in Gherkin syntax**.  

---

## 🛠️ Technologies Used
- **Selenium WebDriver**  
- **JavaScript (Node.js)**  
- **Cucumber (for Gherkin scenarios)**   

---

## ✅ How to Run the Tests  
1️⃣ **Install dependencies**  
```sh
npm install

node testScript.js
