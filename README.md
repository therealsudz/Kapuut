# Kahoot Automation – Security Research Tool

> ⚠️ READ THIS FIRST  
> This project is intended for AUTHORIZED security testing and educational purposes only.  
> If you do not own the environment or have explicit permission — do NOT use it.

---

## 👀 What is this?
A Python + Selenium automation tool created to study how Kahoot handles multiple automated browser clients.

If you're interested in:
- browser automation
- web application behavior
- pentesting fundamentals
- client-side limitations

this project is for you.

---

## 🧠 Why this exists
Modern web applications rely heavily on client-side logic and browser-based protections.  
This project demonstrates:
- automated browser interaction at scale
- concurrency using multithreading
- how web sessions behave under multiple connections
- why proper authorization and rate limiting matter

Built for learning and research — not disruption.

---

## 🛑 Ethical Use Policy (No excuses)
This tool may ONLY be used:
- on systems you own
- on systems you have explicit permission to test
- in controlled, private, or lab environments

❌ Do NOT use this tool against:
- live classrooms
- public Kahoot sessions
- systems you do not own or control

The author is NOT responsible for misuse.

---

## 🛠️ Technical Highlights
- Selenium WebDriver (Chrome, headless)
- Explicit waits (WebDriverWait, Expected Conditions)
- Multithreading via ThreadPoolExecutor
- Dynamic nickname/session handling
- Minimal external dependencies

---

## 📦 Setup

### Requirements
- Python 3.9+
- Google Chrome

Clone the repository:
```bash
git clone https://github.com/therealsudz/Kapuut.git
```

Enter the project directory:
```bash
cd Kapuut
```

Install dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 Usage
Run the script:
```bash
python main.py
```
or python3 depending on installed python version.

You will be prompted for:
- session code
- base nickname
- multithreading configuration

All interaction is done through real browser automation.
You are now ready to run the project.

## 🎓 Who is this for?
- aspiring pentesters
- security researchers
- automation learners
- people curious about client-side web behavior

If your goal is disruption rather than learning — this project is not for you.

## 📄 License
This project is under MIT license.  
You must credit the original author if you reuse or modify this code.
