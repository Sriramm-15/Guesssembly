# ⚔️ Guesssembly: Endgame  

A programming-themed word guessing game (inspired by Wordle + Hangman) where you **save the programming world from Assembly** by guessing the word before time runs out! ⏳  

<img width="1919" height="937" alt="image" src="https://github.com/user-attachments/assets/970d2ecd-577c-4216-86a9-1def63ef1b09" />
<!-- replace with actual screenshot path -->

---

## 🎮 Features  

- 🔤 Word guessing gameplay (like Hangman/Wordle)  
- 💻 Programming languages as your "lives"  
- ⏳ 60-second countdown timer for extra challenge  
- 🎉 Confetti celebration when you win  
- 🎨 Accessible UI with ARIA live regions for screen readers  
- 🕹️ On-screen keyboard  

---

## 🚀 Getting Started  

### 1. Clone the repo  
```
git clone https://github.com/your-username/guesssembly.git
cd guesssembly
```
2. Install dependencies
```
npm install
```
3. Run locally
```
npm start
```
Game will be available at http://localhost:3000.

# 🛠️ Tech Stack

React – Frontend framework
clsx – Conditional class handling
react-confetti – Win animation
Custom word utils – Word randomizer + farewell messages

# 📖 How to Play

You start with 8 attempts (each wrong guess "kills" a programming language).

Click letters to guess the hidden word.

You win if you guess all letters before attempts or time run out.

You lose if all languages are gone or timer hits 0.

# 🖼️ Example
D _ S T _ N C E

Guess wisely! Every wrong guess brings Assembly closer to victory ⚡

# 💡 Future Enhancements

🌐 Multiplayer mode
📊 Score tracking & leaderboards
🎵 Background music / sound effects
🖌️ Custom word packs
