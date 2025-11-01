# Fitness Tracker — C++ Learning Project

A progressive, versioned C++ project for tracking monthly workout consistency while practicing core programming concepts. Each version explores new C++ structures while reinforcing clean code habits, control flow, and modular thinking.

---
## Overview

Part of my hands-on **C++ learning journey**, focusing on:

- Building procedural logic from the ground up

- Practicing functions, loops, conditionals, and input/output

- Structuring maintainable code using **multi-file modularity**

- Managing variable scope and lifetime to reduce intermediary state

- Documenting development phases for clarity and traceability

v4.0 introduces **refactored multi-file structure**, `cin.fail` input validation, and deliberate variable management, preparing the code for scalable future improvements like arrays and structs.

---
## Version Progression

|Version|Focus|Key Features|
|---|---|---|
|`v0`|Manual logic|Fully explicit blocks, no loops or validation|
|`v1`|Grouped logic|Nested switches to reduce duplication|
|`v2.0`|Iteration|`for` loops for input/output, no validation|
|`v2.1`|Input validation|Range checks using `if`, retry handling|
|`v2.2`|Error handling prep|`do-while` loops, loop limiter for bad input, groundwork for type checks|
|`v3.0`|Modular refactor|Functions for input, validation, calculation, level assignment, output; while-loop input validation; reusable workflow|
|`v4.0`|Multi-file refactor|Separated logic into headers and `.cpp` files, `cin.fail` input validation, minimized intermediary variables, explicit variable lifetime management, modularized input/output|

---
## Core Concept

Tracks **four workout types**: Upper Body, Lower Body, Core, Cardio

- Users enter weekly workouts over 4 weeks

- Program totals monthly frequency, assigns fitness level, and outputs feedback


**Frequency Categories:**

- 0–7: insufficient (level 1)

- 8–21: good consistency (level 2)

- 22–28: excellent (level 3) (unrealistic but simplistic levels for now to practice)

---
## Learning Objectives (v4.0)

- Multi-file C++ project organization and header/source file usage

- Input validation using `cin.fail`

- Modularization of functions across files for clarity and reuse

- Managing **variable scope and lifetime**, reducing unnecessary intermediaries

- Condensing `main()` while preserving program flow and readability

- Incremental design and structured documentation

---
## How to Use

1. Clone the repository:
git clone https://github.com/s-0-p-h-i-a/Fitness_Tracker.git

2. Compile the code using a C++ compiler (example for v4.0):
g++ src/main.cpp src/*.cpp -o fitness_tracker_v4

3. Run the program:
./fitness_tracker_v4

4. Follow the on-screen prompts to enter your workouts.

---
## Files & Structure

- `src/main.cpp` → lightweight entry point; orchestrates function calls

- `src/inputValidation.cpp/.h` → consolidated `cin.fail` input handling

- `src/printInput.cpp/.h` → outputs intermediary value: monthly totals per workout type

- `src/getMonthlyTotal.cpp/.h` → monthly total calculations

- `src/getResults.cpp/.h` → computes fitness level from totals and feedback comment

- `src/getWorkoutType.cpp/.h` → reusable function to emulate array-like workout types "directory"
- `src/output.cpp/.h` → handles output formatting and display

- `README.md` → this file

- Devlogs → version-specific development notes


> Each `.cpp/.h` pair is organized for clarity, and headers contain function declarations only. `main.cpp` remains concise and readable.

---
## Future Directions

- Replace repeated variables with **arrays/structs** for cleaner loops and scalable design

- Expand to **variable-length months** and multi-month tracking

- Integrate **more nuanced feedback and level assignment**

- Optionally visualize progress via **text-based summaries or graphs**

---
## Documentation Workflow & AI Assistance

All documentation is based on original engineering notes taken during development. AI is used selectively to assist with formatting and summarizing, but all code decisions are manually verified. Raw notes are preserved for traceability.
