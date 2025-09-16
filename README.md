# 👋 Hi, I’m Álvaro Magalló Paz

In my professional life, I’m always driven by the following question:

> *How can we model the mind, with all its emergent logic, memory, and constraints, using the rigor of hardware, mathematics, and systems design?*

## 🧠 What defines my work

Since my teenage years, I’ve viewed the mind as a modelable structure **emerging** from matter, not as something separate from it. During my **Computer Engineering** studies, that idea evolved into a deep interest in the intersection between Computer Science and Psychology, leading me to focus on **hardware-level emulation and formal verification** of cognitive architectures.

My work bridges **symbolic rigor and neural realism**, developing interpretable systems that respect cognitive dynamics through **traceability**, **formal methods**, **symbolic modeling**, and **biologically inspired design**.

## 🔍 What I build

### 🧪 Neuromorphic Hardware Development
 
- **Circuit simulation** of circuits in VHDL-AMS representing simplified neuronal dynamics  
- **Symbolic translation** of analog behavior into SMT constraints using Z3  
- **Full traceability** graph (Requirements → Properties → Implementation → Verification)  
- **Compliance** with DO-254 and DO-333 standards (critical systems engineering)

### 🧱 Tiny Compiler Design

- Designed a **full compiler toolchain** for **Tiny**, a procedural programming language  
- **AST implementation** in Java 17 using record types, memoized reflection dispatch  
- Custom **p-code virtual machine** with typed instructions, stack frames, memory manager  
- **Structured types** (arrays, records, pointers), by-reference / by-value handling, exception control  
- VM memory modeled on **two-level RAM** structures with FAT-style **dynamic heap**

🔗 [Source Code on GitHub](https://github.com/amagallo/tiny-compiler)

### 🔢 Purely Functional Hashing

- **Interactive console application** in Haskell implementing a hash table based on Mersenne primes
- Built custom **big integer API** with boolean lists and using Karatsuba multiplication
- Implemented optimized **Lucas-Lehmer test** for prime verification
- Integrated advanced **remainder algorithms** specific for Mersenne-like numbers
- Used **balanced trees** as array substitutes to achieve logarithmic-time access

🔗 [Source Code on GitHub](https://gist.github.com/amagallo/f15bf0258bc8da12a8103a4e13c6b149)

### 🧠 Human Connectome Analysis 
- Analyzed **effective connectivity** using Rolls & Deco’s resting-state algorithm  
- Processed HCP S1200 data and parcellated brain maps using the extended HCPex atlas (180×2 ROIs)  
- Extracted both **resting-state** and **task-related** networks  
- Axial **visualization** of connectomes, aligned with dynamic fluctuations in functional connectivity

### ⛏ Mining Game Programming

- **Console-based mining game** in C++ for Windows, rendered entirely in **ANSI-colored** ASCII
- **Rebuilt UI** with escape sequences for a dynamic **retro feel**
- Designed **full player-facing interface** with authentication, score tracking, and session persistence
- Gameplay featured gem collection, obstacles, gravity-based physics, TNT clearing, and strategic scoring
- **Switchable board sizes** enabled different cognitive perspectives for level solving

## 🛠 Technical Stack

- **Formal Methods**: Z3, SMT, logical modeling, invariants, assertions  
- **Hardware Design**: VHDL-AMS, Siemens PartQuest, MBSE, DO-254/DO-333  
- **Languages**: Python, Java, Haskell, Elixir, C++, DSL design  
- **Mathematics**: symbolic systems, algebra, graph theory, category theory  
- **Modeling**: connectomics, artificial neural systems, verification pipelines

## 🌍 What I believe

> “Technology should be rigorous, and human.
Not just correct, but interpretable.
Not just fast, but meaningful.”

I believe that building systems isn’t just about logic, it’s about responsibility.
Creating technology that mirrors the mind requires not only formal control, but also a sense of care: for how we think, how we live, and how we relate to one another.

My commitment to science is inseparable from my commitment to people. I see engineering not as an abstract discipline, but as a way to **build bridges between minds**, combining **aerospace-level discipline**, **philosophical clarity**, and **human-centered design** to shape systems that reflect both **rigor and empathy**.