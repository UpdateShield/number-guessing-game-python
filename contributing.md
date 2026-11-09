# 🎲 Number Guessing Game Python

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,13,6&height=210&section=header&text=Number%20Guessing%20Game&fontSize=56&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Guess%20Smart.%20Learn%20Python.%20Have%20Fun.&descAlignY=56&descSize=19" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.0.0-06D6A0?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Python](https://img.shields.io/badge/Python-3.8+-118AB2?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-073B4C?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Modes](https://img.shields.io/badge/modes-4-EF476F?style=for-the-badge&logo=gamepad&logoColor=white)](https://github.com)

<br/>

### 🎯 A fun, beginner-friendly number guessing game — CLI & GUI, endless replay value

*🖥️ Terminal & GUI • 🏆 Difficulty Levels • 💡 Smart Hints • 📊 Score Tracking*

<br/>

<a href="https://share.google/L8f0irFzLBMBbJS79">
  <img src="https://img.shields.io/badge/📥_GET_CODE-06D6A0?style=for-the-badge&logo=github&logoColor=white&labelColor=04A67C" alt="Get Code" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/L8f0irFzLBMBbJS79">
  <img src="https://img.shields.io/badge/🚀_PLAY_ONLINE-118AB2?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0C6482" alt="Play Online" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/L8f0irFzLBMBbJS79">
  <img src="https://img.shields.io/badge/📚_DOCS-EF476F?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=BF3859" alt="Docs" height="45"/>
</a>

</div>

<img width="1100" height="640" alt="guess-the-number_3" src="https://github.com/user-attachments/assets/833b92b5-ba4a-4385-83fe-557213747395" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Number Guessing Game Python** is a polished, beginner-friendly take on the classic number guessing game. Pick a difficulty, guess a number, and get **smart hints** that guide you to the answer — all while learning clean Python patterns along the way.

It ships with **four play modes**, a **GUI version** for desktop fun, and **full score tracking** that saves your best results between sessions.

> 💡 **Perfect for:** Python beginners, coding teachers looking for a fun classroom demo, and anyone who enjoys quick logic puzzles.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🎮 **4 Game Modes** | 🏆 **Difficulty Levels** | 💡 **Smart Hints** |
|:---:|:---:|:---:|
| Classic, timed,<br/>reverse & endless | Easy, medium,<br/>hard & insane | Hot/cold feedback<br/>with distance hints |

| 🖥️ **CLI + GUI** | 📊 **Score Tracking** | 🎨 **Clean Code** |
|:---:|:---:|:---:|
| Play in terminal<br/>or desktop window | Best scores saved<br/>between sessions | Beginner-readable,<br/>well-commented |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Game

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🎓 **Learn by Playing** | Code is simple enough for a beginner to read and modify |
| 🧠 **Real Logic Practice** | Binary search thinking, feedback loops, and probability |
| ⚡ **Instant Startup** | No install, no dependencies — just `python game.py` |
| 🎨 **Two Interfaces** | Terminal for learning, GUI for fun and screenshots |
| 📊 **Persistent Scores** | Tracks best attempts, average guesses, and streaks |
| 🔧 **Extendable** | Clean architecture invites you to add your own modes |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Game Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🎲  Number Guessing Game  v2.0.0                ║
╠══════════════════════════════════════════════════╣
║  Difficulty: Medium  (1 – 100)                   ║
║  Attempts left: 7                                ║
║  ──────────────────────────────────────────      ║
║  Your guess: 50                                  ║
║  📉 Too low!   (getting warmer...)               ║
║                                                  ║
║  Your guess: 75                                  ║
║  📈 Too high!  (burning hot!)                    ║
║                                                  ║
║  Your guess: 63                                  ║
║  🎯 CORRECT!  You got it in 3 guesses!           ║
║                                                  ║
║  🏆 Personal best: 3 guesses (Medium)            ║
║  📊 Streak: 5 wins in a row                      ║
║  🔁 Play again?  [ Y / n ]                       ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🎲 number-guessing-game-python/
├── 🎯 src/
│   ├── game/                  # Game logic
│   │   ├── core.py
│   │   ├── modes.py
│   │   └── hints.py
│   ├── cli/                   # Terminal interface
│   ├── gui/                   # Desktop (Tkinter) interface
│   └── scores/                # Score persistence
├── 🧪 tests/                  # Unit tests
└── 📖 docs/                   # How to play & how to extend
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-3776AB?style=for-the-badge&logo=python&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Want a new game mode? Have an idea to make it more fun?

<div align="center">

<a href="https://share.google/L8f0irFzLBMBbJS79">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/L8f0irFzLBMBbJS79">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-073B4C?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/L8f0irFzLBMBbJS79">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-06D6A0?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 🎲 Made with 🐍 by the Guessing Game Team

*If this game made you smile (or curse at "too high") — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,13,6&height=120&section=footer" width="100%"/>

</div>
