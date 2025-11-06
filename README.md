# 🧠 Alan Turing Summary + Quiz Project

This project scrapes the [Alan Turing Wikipedia page](https://en.wikipedia.org/wiki/Alan_Turing),
generates a short summary, builds a multiple-choice quiz, and stores everything in a SQLite database.

## ⚙ Setup Instructions

### Option 1 – Run in Google Colab (recommended)
1. Go to [Google Colab](https://colab.research.google.com)
2. Upload main.py
3. Run all cells — dependencies install automatically.

### Option 2 – Run locally
```bash
# 1️⃣ Clone or unzip this project
cd alan_turing_quiz_project

# 2️⃣ Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate      # on Windows: venv\Scripts\activate

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Run the script
python main.py


### ✅ Scraped and summarized: Alan Turing

### 📖 Summary:
Alan Turing was a British mathematician and computer scientist...

## 🧩 Let's take a quiz!
Q1. In which year was Alan Turing born?
   1. 1902
   2. 1912
   3. 1922
   4. 1932
✅ Correct!

### 🏁 Your final score: 4/5
### 📦 Database saved as: alan_turing_quiz.db
