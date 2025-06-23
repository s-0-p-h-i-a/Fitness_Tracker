# 🏋️‍♀️ Fitness Tracker — C++ Learning Project

A progressive, versioned C++ project for tracking monthly workout consistency while practicing fundamental programming structures. Each version explores new C++ concepts while reinforcing clean code habits, manual control flow, and modular thinking without abstraction tools.

---
## 📌 Overview

This project is part of my hands-on learning journey with **C++**, focusing on:

- Building procedural logic from the ground up
    
- Practicing core programming concepts (loops, conditionals, input/output)
    
- Designing maintainable code before using advanced tools like arrays or functions
    
- Structuring and documenting each development phase with care and clarity
    

Each version adds one or more new concepts while preserving readability and traceability.  

---
## 📆 Version Progression

| Version | Focus             | Key Features                                      |
| ------- | ----------------- | ------------------------------------------------- |
| `v0`    | Manual logic only | Fully explicit blocks with no loops or validation |
| `v1`    | Grouped logic     | Nested switches to reduce duplication             |
| `v2.0`  | Iteration         | `for` loops for input/output, no validation       |
| `v2.1`  | Input validation  | Range checks using `if` logic, retry handling     |

---
## 🧠 Core Concept

Each version tracks **four workout types**:

- Upper Body
    
- Lower Body
    
- Core
    
- Cardio
    

Users enter how often they completed each type per week over 4 weeks. The program:

- Totals monthly frequency for each workout type
    
- Classifies performance level
    
- Outputs personalised feedback
    

---
## 🔧 Learning Objectives

This project helps me practice and understand:

- 📥 Input/output operations
    
- 🔁 Loop structures (`for`)
    
- 🧭 Branching (`if`, `switch`)
    
- 🧱 Manual modularity and code reuse
    
- 🧪 Input validation strategies
    
- 🧠 Control over program flow and variable scope
    
- 📝 Incremental design and documentation practices


---
## 📝 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/s-0-p-h-i-a/Fitness_Tracker.git

2. Choose a version then compile the code using a C++ compiler:
    ```bash
   g++ fitness_tracker_v2_1.cc -o fitness_tracker_v2_1

4. Run the program:
      ```bash
    ./fitness_tracker_v2_1

5. Follow the on-screen prompts to enter your workouts.

---
## 🗃️ Files & Structure

- `fitnesstracker_v0.cc`: fully manual, verbose version
    
- `fitnesstracker_v1.cc`: grouped logic using nested `switch` structures
    
- `fitnesstracker_v2_0.cc`: introduces `for` loops
    
- `fitnesstracker_v2_1.cc`: adds input validation (0–7 range)
    
- `README.md`: this file
    
- Devlogs: cleaned-up version-specific development logs
    

Each `.cc` file begins with an in-code documentation block derived from raw notes.

---
## 🚀 Future Directions

Planned improvements as I deepen my C++ knowledge:

- Use **arrays** to simplify data storage
    
- Create **functions** for modularity and reuse
    
- Implement **more robust input validation** (e.g. type checking)
    
- Allow **custom workout goals** and longer time spans
    
- Track **workout distribution** (e.g., even vs. clumped activity)
    
- Visualize progress using **text-based summaries or graphs**
    

---
### 🧠 Documentation Workflow & AI Assistance

All documentation in this project (README, dev logs, and code comments) is based on original engineering notes taken during development. These notes are written manually on top of the `.cc` source file as I work.

To improve clarity and structure, I use AI tools selectively to assist with formatting, polishing, and summarising the content — particularly for:
- Drafting new README versions based on raw notes and previous versions
- Generating development logs that clearly trace design decisions, also based on raw notes and previous versions
- Condensing raw notes into opening in-code documentation blocks

All AI-assisted outputs are reviewed and edited by me. No code, decisions, or technical content are generated or altered without verification and approval.  
Raw notes are preserved in a dev diary folder for traceability and transparency.

This workflow is designed to maintain both high clarity and authorship integrity.

---

**Made with C++, consistency, and curiosity.**  
_This project documents my learning journey toward embedded systems and structured programming._ 🛠️
