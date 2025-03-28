# 🏠 Student Apartment Recommender Chatbot for Texas A&M University

This project presents an interactive **chatbot system** built from scratch to recommend **off-campus apartments** for students near **Texas A&M University** (College Station and Bryan). Using a custom-built dataset, the chatbot helps users find housing based on their preferences — such as price, number of bedrooms, bus access, furnishing, and more.

📘 Course Project – *Human AI Interaction*  
👥 Team Members: Ishant Kundra, Aashay Kadakia, Rahaan Gandhi

---

## 🤖 Project Overview

We designed a **natural language-based assistant** that provides personalized apartment recommendations. Unlike traditional search engines, this chatbot allows students to interactively filter results, receive top suggestions, and refine their preferences during conversation.

---

## 📂 Repository Structure

<pre>
Student-Apartment-Chatbot/
│
├── Code/                   
│   ├── chatbot_GUI.py              # Chatbot interface (Tkinter GUI)
│   ├── recommend.py                # Recommendation engine logic
│   ├── dataframe.py                # Dataset cleaning & preprocessing
│   └── runfirst.sh                 # Startup script (optional)
│
├── Dataset/
│   ├── apartments.csv              # Raw scraped dataset
│   ├── cleaned_data.csv            # Processed dataset for chatbot
│   └── dataset.csv                 # Additional reference data
│
├── Report/
│   └── Student Dorm Recommender.pdf  # Project report with design, flow, evaluation
│
└── README.md
</pre>

---

## 💡 Features

- 💬 Conversational chatbot interface using **Tkinter**
- 🏠 Apartment filtering based on:
  - Bedrooms, bathrooms, rent range
  - Bus access, pet-friendly, parking, furnished
- 🔄 Support for:
  - Showing top 5 preferred apartments
  - Asking for new options if dissatisfied
  - Modifying preferences mid-conversation
- 🧠 Built using **spaCy** for rule-based NLP (no pre-trained LLMs)
- 📋 Dataset built manually by searching real listings across **College Station & Bryan, TX**

---

## ⚙️ Technologies Used

- Python 3.10  
- Pandas, NumPy  
- spaCy (for NLP)  
- Tkinter (GUI)  
- CSV (dataset storage)

---

## 🚀 How to Run

### Step 1: Set up environment
Make sure Python 3.10+ is installed.

```bash
pip install pandas numpy spacy
python -m spacy download en_core_web_sm

Step 2: Preprocess (Optional)

python Code/dataframe.py

Step 3: Launch Chatbot

python Code/chatbot_GUI.py

Ensure cleaned_data.csv exists in the Dataset/ folder before launching the chatbot.
```
---
<pre>
📈 Evaluation Summary
	•	✅ Tested with 200 TAMU students (including international students)
	•	👍 Easy to use for new students unfamiliar with housing options
	•	🔄 Flexible: Allows asking for more results or updating preferences
	•	🗨️ Most praised features:
	•	Bus route filtering
	•	Price range control
	•	Dynamic conversation
</pre>
---
<pre>
🚧 Future Improvements
	•	🤝 Add fuzzy matching and user slang support
	•	🌐 Build a web interface using Flask or React
	•	📍 Integrate live data from Zillow, Apartments.com, or Google Maps
	•	🧠 Add user profiles and memory for long-term recommendations
</pre>
---

📄 Report
	•	Project Report: Student Dorm Recommender.pdf

---

👨‍💻 Authors

Ishant Kundra
M.S. Computer Science, Texas A&M University
📧 ishantkundra9@gmail.com

Aashay Kadakia
M.S. Computer Science, Texas A&M University

Rahaan Gandhi
M.S. Computer Science, Texas A&M University
