# Fitness Tracker — C++ Learning Project

A progressive, versioned C++ project for tracking monthly workout consistency while practicing core programming concepts. Each version explores new C++ structures while reinforcing clean code habits, control flow, and modular thinking.

---
## Overview

Part of my hands-on **C++ learning journey**, focusing on:

- Building procedural logic from the ground up

- Practicing functions, loops, conditionals, and input/output

- Structuring maintainable code before advanced tools (arrays, structs)

- Documenting development phases for clarity and traceability

v3.0 introduces **modular functions** for input, validation, calculation, feedback, and output, preparing for scalable, reusable code.

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

---
## Core Concept

Tracks **four workout types**: Upper Body, Lower Body, Core, Cardio

- Users enter weekly workouts over 4 weeks

- Program totals monthly frequency, assigns fitness level, and outputs feedback

**Frequency Categories:**

- 0–7: insufficient (level 1)

- 8–21: good consistency (level 2)

- 22–28: excellent (level 3)

---
## Learning Objectives

v3.0 helps practice:

- Procedural input/output operations

- Loop structures (`for`, `while`) and branching (`if`, `switch`)

- Function-based modularity and reusable logic

- Input validation strategies

- Defensive programming under constraints

- Control over variable scope and program flow

- Incremental design and documentation habits

---
## 📝 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/s-0-p-h-i-a/Fitness_Tracker.git
```

2. Choose a version then compile the code using a C++ compiler:
```bash
   g++ fitness_tracker_v2_1.cc -o fitness_tracker_v2_1
```

3. Run the program:
 ```bash
   ./fitness_tracker_v2_1
```

4. Follow the on-screen prompts to enter your workouts.

---
## Files & Structure

- `fitnesstracker_v0.cc` → manual, verbose version

- `fitnesstracker_v1.cc` → grouped logic with nested switches

- `fitnesstracker_v2_0.cc` → introduces `for` loops

- `fitnesstracker_v2_1.cc` → adds range-based input validation

- `fitnesstracker_v2_2.cc` → do-while loops, loop limiter, groundwork for type checking

- `fitnesstracker_v3_0.cc` → modular refactor with functions, while-loop validation, and reusable workflow

- `README.md` → this file

- Devlogs → version-specific development notes


Each `.cc` file starts with an in-code documentation block derived from raw notes.

---
## Future Directions

- Replace repeated variables with **arrays/structs** for scalability

- Expand to **variable-length months** and **multi-month cycles**

- Integrate **type-safe input** using `cin.fail()`

- Further modularize input + validation logic

- Add nuanced feedback and realistic level assignment

- Optionally visualize progress via **text-based summaries or graphs**

---
## Documentation Workflow & AI Assistance

All documentation is based on original engineering notes taken during development. AI is used selectively to assist with formatting, summarizing, and polishing, but all code decisions are manually verified. Raw notes are preserved in a dev diary for traceability.

This workflow ensures high clarity and authorship integrity.
