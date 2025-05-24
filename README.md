# 📝 Spelling & Grammar Corrector using NLP (Flask + NLTK + TextBlob)

This is an NLP-based web application that automatically detects and corrects **spelling and grammar errors** in English text using **TextBlob** and **NLTK**, with a simple web interface built using **Flask**.

Users can **enter text manually** or **upload `.txt` files**, and the app will provide corrected output instantly. This tool is ideal for writers, students, and professionals who want to improve the quality of their written English.

## 🚀 Features

- 🔤 Spelling correction using `TextBlob`
- 📘 Basic grammar checking and POS tagging with `NLTK`
- 📂 Upload `.txt` files for batch correction
- 🧾 View original and corrected text side-by-side
- 💡 Simple and intuitive Flask-based interface

## 📦 Technologies Used

- **Backend:** Python, Flask
- **NLP:** TextBlob, NLTK
- **Frontend:** HTML, CSS, Bootstrap (optional)
- **File Support:** `.txt` file input

## 🧠 How It Works

1. User inputs text or uploads a `.txt` file.
2. Flask server receives and processes the text.
3. `TextBlob` performs spelling corrections.
4. `NLTK` is used for sentence and word tokenization, optionally for grammar enhancement.
5. Corrected text is displayed alongside the original.
