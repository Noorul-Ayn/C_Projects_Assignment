# C Programming Projects
**Student ID: 54321**

Three C projects demonstrating dynamic memory allocation, pointers, function pointers, structs, and unions.

---

## Project 1: Dynamic Student Record Engine

A student record management system that stores and analyzes academic data.

**Compile & Run:**
```bash
gcc -o project1 project1.c -lm
./project1
```

**Features:** Add students, display records, sort by grade, calculate average, find top student, and run a Grade Stability Score analysis.

---

## Project 2: Adaptive Text Intelligence Tool

A text analysis tool that processes a paragraph and computes word and character statistics.

**Compile & Run:**
```bash
gcc -o project2 project2.c
./project2
```

**Features:** Word count, longest word, most frequent word, and Vowel Density analysis. Memory addresses of key data structures are printed on startup.

---

## Project 3: Callback-Based Device Monitoring Simulator

A device monitoring simulator that processes sensor readings using callback functions.

**Compile & Run:**
```bash
gcc -o project3 project3.c
./project3
```

**Features:** Simulates 10 random readings from temperature sensors, pressure gauges, and voltage meters. Includes a custom Battery Health Monitor callback.

---

## Requirements

- GCC compiler
- Linux / Ubuntu
- `-lm` flag required only for Project 1 (math library)
