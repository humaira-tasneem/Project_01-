📞 Call Management System (C++)

A console-based call center simulation built in C++ using a queue data structure and object-oriented programming. Incoming calls wait in a queue and are automatically routed to free agents.

✨ Features
Queue-based waiting system: calls are served in the order they arrive (FIFO)
Automatic routing: a waiting call is assigned to the next free agent
Call completion: agents can finish calls and become available again
Call history: every handled call is recorded
Menu-driven interface: simple console menu, no setup needed
🧠 Concepts Used
Queue (FIFO) data structure
Classes and objects (OOP)
Header / source file separation (.h and .cpp)
📁 Project Structure
.
├── agent.h / agent.cpp          # Agent class
├── call_queue.h / call_queue.cpp # Queue for waiting calls
├── system.h / system.cpp        # Routing and call management logic
├── main.cpp                     # Entry point and menu
└── README.md
⚙️ How to Compile

Make sure you have a C++ compiler such as g++ installed, then run this from the project folder:

bash
g++ src/*.cpp -o call_system
▶️ How to Run

Linux / WSL / macOS

bash
./call_system

Windows

bash
call_system.exe
🚀 Possible Improvements
Add call priorities (for example, VIP callers first)
Save call history to a file
Track call duration and agent statistics
