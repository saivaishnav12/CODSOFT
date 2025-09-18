# Task 1  chatbot
# Simple Python Chatbot

This is a basic chatbot written in Python. It replies to greetings, farewells, and some simple questions by matching keywords in your input.

---

## How to Run

1. Make sure you have Python installed.
2. Run the chatbot script:

```bash
python chatbot.py

sample output
Chatbot: Hi! I'm your friendly chatbot. Type 'bye' to end the chat.
You: hello
Chatbot: Hey!

You: how are you
Chatbot: I'm doing great!

You: what's your name?
Chatbot: I'm a chatbot made to talk with you!

You: bye
Chatbot: Goodbye!
```
# Task2 tic-tac-toe

This is a command-line Tic-Tac-Toe game where you play against an AI opponent.  
The AI uses the **Minimax algorithm** to always play optimally.

---

## How to Play

- You are **X** and the AI is **O**.
- The board positions are numbered 1 to 9 like this:

```bash
python tictactoe.py

sample output
Welcome to Tic-Tac-Toe! You are 'X'. AI is 'O'.
 | | 
-----
 | | 
-----
 | | 

Enter your move (1-9): 5
 | | 
-----
 |X| 
-----
 | | 

AI chooses: 1
O| | 
-----
 |X| 
-----
 | | 

Enter your move (1-9): 9
O| | 
-----
 |X| 
-----
 | |X

AI chooses: 3
O| |O
-----
 |X| 
-----
 | |X

Enter your move (1-9): 7
O| |O
-----
 |X| 
-----
X| |X

AI chooses: 4
O| |O
-----
O|X| 
-----
X| |X

Enter your move (1-9): 8
O| |O
-----
O|X| 
-----
X|X|X

You win!
```
# Task4 recommendation system
# Movie Recommendation System

This is a simple movie recommendation system implemented in Python.  
It recommends movies based on the similarity of their descriptions using **TF-IDF** and **cosine similarity**.

---

## How It Works

- Uses movie titles and their descriptions.
- Converts descriptions to TF-IDF vectors.
- Calculates cosine similarity between movies.
- Recommends movies similar to the one you input.

---

## How to Run

1. Make sure you have Python installed.
2. Install required libraries if needed:

```bash
pip install pandas scikit-learn
#run
python recommend.py

sample output
Enter a movie title: Interstellar

Recommendations:
- Inception
- The Matrix
- Avengers: Endgame
- The Dark Knight
- John Wick
```
