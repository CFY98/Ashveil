A text-based RPG set in the fictional world of Ashveil. The player must pass three levels, each getting progressively harder to complete. The game features a trivia-based combat system influenced by Game Shows. Enjoy~

<<<<<<< HEAD
Developed as part of the CodeNation LV2 Coding Course in a team of 2 (formerly 3) people.
=======
Team
- Project Manager - CN
- Head Developer - CFY
  
📖 Story Overview
Your adventure begins in a sleepy inn at the edge of a small village. From there, you'll navigate morally complex encounters, rescue a kidnapped princess, and ultimately face a climactic battle at the foot of an erupting volcano. But the path you take — and the choices you make — will shape the ending you deserve.
>>>>>>> 0dc498d (Enhance README with detailed project information)

Inn (Character Creation)
 └── Level One: Village
      ├── Speak with the Lord → fight a bandit or flee
      └── Speak with the Bandit → help steal or fight him
           └── Level Two: Station & Castle
                └── Throne Room → Accept or Deny the King's Quest
                     └── Level Three: Mountain → Wizard's Lair → Volcano
                          ├── Good Ending: Slay the Dragon 🐉
                          └── Bad Ending: Fight the King 👑

✨ Features

- Procedurally generated names — kings, wizards, princesses, villages, and towns are randomly generated each playthrough
- Karma system — your choices throughout the game silently shift your alignment, determining the final battle and ending
- Turn-based combat — fight enemies by answering trivia questions fetched live from an open-source trivia database
- Inventory system — collect and use potions (restore health) and poison (damage over time across multiple turns)
- Health bars — colour-coded, dynamic health bars for both player and enemies
- ASCII art titles — stylised banners for each level, game start, and both endings
- Multiple branching paths — decisions in Level One and Two lead to different encounters and alter the ending

<<<<<<< HEAD
<<<<<<< HEAD
For Windows, please download the .exe file.
=======
For Windows, please download the "Ashveil.exe".

For MacOS, please download "Ashveil".
>>>>>>> d0e8a64 (Add MacOS download instructions to README)
=======
🎮 How to Play
Prerequisites

- Python 3.10 or higher (required for match/case syntax)
- An active internet connection (trivia questions are fetched live)

Installation
git clone https://github.com/yourusername/cycles-end.git
cd cycles-end

- For Windows, please download the "Ashveil.exe".
- For MacOS, please download "Ashveil".
- For Linux, please download "Ashveil_linux". 
# Not too familiar with Linux but hopefully this can run on all distros.

Running the game
python main.py

⚔️ Combat System
Combat is trivia-based. Each round, you:
- Choose to Fight or Use Item
- If you fight, a multiple-choice trivia question is displayed
- Answer correctly → deal random damage (1–100) to the enemy
- Answer incorrectly → take that damage yourself

Project Structure
Ashveil/
│
├── main.py          # All game logic, combat, narrative, and mechanics
└── README.md

🌐 Trivia Source
Questions are fetched live from the OpenTriviaQA dataset (general category). An internet connection is required to play.

🛠️ Known Limitations

Health cannot exceed 100 (potions may overheal beyond the visual bar)
The game has no save system — each session starts fresh
Terminal colour support requires a compatible console (works on macOS, Linux, and Windows Terminal)

📄 License
This project is licensed under the MIT License.
>>>>>>> 0dc498d (Enhance README with detailed project information)
