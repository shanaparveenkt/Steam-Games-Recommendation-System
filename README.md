# 🎮 Game Recommendation System using Content-Based Filtering

A content-based game recommendation system built using Python and machine learning techniques.  
This project recommends similar Steam games based on a user’s favorite game by analyzing textual features such as genre, tags, game details, developer, and publisher.

---

## 📌 Project Overview

With thousands of games available on platforms like Steam, users often find it difficult to choose games that match their interests.  
This project implements a **content-based recommendation system** using **Natural Language Processing (NLP)** techniques.

The system analyzes game-related text data and suggests games that are most similar to the game entered by the user.

---

## 🎯 Objectives

- Build a content-based game recommendation system  
- Apply TF-IDF vectorization for text feature extraction  
- Use cosine similarity to measure similarity between games  
- Recommend relevant games based on user input  

---

## 🚀 Features

- Content-based recommendations  
- User-friendly input system  
- TF-IDF text vectorization  
- Cosine similarity for similarity measurement  
- Efficient handling of missing values  

---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, difflib  
- **Tools:** Jupyter Notebook / Google Colab  

---

## 📂 Dataset

- **Dataset:** Steam Games Dataset (`steam_games.csv`)  
- **Key Features Used:**  
  - name  
  - genre  
  - popular_tags  
  - game_details  
  - developer  
  - publisher  

---

## ⚙️ Working Methodology

1. Load the Steam games dataset  
2. Perform data exploration and preprocessing  
3. Select relevant textual features  
4. Replace missing values with empty strings  
5. Combine selected features into a single text column  
6. Convert text into numerical vectors using TF-IDF  
7. Compute similarity using cosine similarity  
8. Recommend similar games based on user input  

---

## ▶️ How to Run the Project

### Step 1: Clone the repository
Step 2: Install Required Libraries
pip install numpy pandas scikit-learn
Step 3: Run the Project
python game_recommendation.py
Step 4: Enter Your Favorite Game Name
When prompted, enter a game name from the dataset to get similar game recommendations.

## 📈 Sample Output

Enter your favourite game name : GTA V
Games suggested for you :
1. Red Dead Redemption 2
2. Watch Dogs
3. Sleeping Dogs
4. Mafia II
5. Just Cause 3

## 🎯 Applications
- Game recommendation platforms
- Beginner-level machine learning projects
- NLP-based similarity analysis
- Academic mini and major projects

## 🔮 Future Enhancements
- Add collaborative filtering using user ratings
- Build a web-based interface using Streamlit or Flask
- Improve recommendation accuracy using advanced NLP models

## 👩‍💻 Author
Shana Parveen K T
Data Science Learner | Python Enthusiast

This project is created for learning and educational purposes.

