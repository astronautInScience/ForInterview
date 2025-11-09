
# 🧠 Booking.com Coding Assessment — Concept Notes

This document summarizes all **key computer science and algorithm concepts** tested during the Booking.com HackerRank-style exam, with explanations, examples, and quick references.

---

## 📘 1. FizzBuzz Problem (Programming Logic & Loops)

**Concepts Tested:**
- Conditional statements (`if`, `else if`, `else`)
- Loops (`for` loop)
- Modulo operator (`%`)
- String output formatting

**Example (C code):**
```c
for (int i = 1; i <= n; i++) {
    if (i % 3 == 0 && i % 5 == 0) printf("FizzBuzz\n");
    else if (i % 3 == 0) printf("Fizz\n");
    else if (i % 5 == 0) printf("Buzz\n");
    else printf("%d\n", i);
}
```

**Purpose:** Tests your ability to handle basic logic flow and conditions efficiently.

---

## 🧮 2. Score Difference Problem (Data Structures & Game Simulation)

**Concepts Tested:**
- Array traversal
- Directional iteration (using pointers or indices)
- Conditional reversal
- Turn-based logic

**Core Idea:**
You simulate players alternately removing elements from a sequence and reversing based on conditions (e.g., if a number is even).

**Key skills:**
- Using indices instead of copying arrays
- Maintaining cumulative sums (scores)
- Applying `if` logic to control flow

---

## 🔡 3. Fun with Anagrams (String Manipulation & Hashing)

**Concepts Tested:**
- Detecting anagrams via sorting or frequency counting
- Nested loops & string comparison
- Memory allocation and cleanup
- Sorting final output (`qsort` in C)

**Key Concept:**
Two strings are anagrams if they contain the same characters in different order.

**Example:**
```
"code" and "doce" → anagrams
"frame" and "framer" → not anagrams
```

**Solution Steps:**
1. For each word, check if any later word is its anagram.
2. Keep only the first occurrence.
3. Sort and print remaining unique words.

---

## 🕒 4. Big O Notation (Algorithm Complexity)

**Concepts Tested:**
- Understanding growth rates of algorithms
- Recognizing asymptotic notation meanings

| Notation | Meaning | Represents |
|-----------|----------|------------|
| **O(n)** | Upper bound | Worst-case runtime |
| **Ω(n)** | Lower bound | Best-case runtime |
| **Θ(n)** | Tight bound | Average-case runtime |

**Example:**
- `O(1)` → Constant time
- `O(n)` → Linear time
- `O(n log n)` → Log-linear (e.g., mergesort)
- `O(n²)` → Quadratic (e.g., nested loops)

---

## 🔗 5. Articulation Points (Graph Theory)

**Concepts Tested:**
- Depth-first search (DFS) understanding
- Connected components in graphs
- Critical node identification

**Definition:**
An **articulation point** (or **cut vertex**) is a vertex whose removal increases the number of connected components in a graph.

**Example Graph:**
```
0—2—3—6
   |  |
   4—1—5
```

**Articulation Points:** 2, 3, 1

**Key Use Cases:**
- Network reliability analysis
- Bridge node detection
- DFS time tracking algorithms (Tarjan’s Algorithm)

---

## ⚙️ 6. General Programming Concepts Covered

| Concept | Description |
|----------|--------------|
| **Arrays** | Fixed-size sequential data structures |
| **Strings** | Character arrays manipulated via functions like `strcmp`, `strcpy` |
| **Pointers** | Used for dynamic memory in C |
| **Dynamic Memory** | `malloc`, `calloc`, and `free` for runtime allocation |
| **Sorting Algorithms** | Bubble sort, selection sort, or `qsort()` in C |
| **Time Complexity** | Performance evaluation metric for algorithms |
| **Graphs & Trees** | Nodes and edges representing relationships |
| **Recursion & DFS** | Fundamental for graph exploration and problem decomposition |

---

## 🧩 7. Recommended Preparation Topics for Booking.com

1. **Data Structures:**
   - Arrays, Strings, Linked Lists, Stacks, Queues
2. **Algorithms:**
   - Sorting (Quick, Merge, Insertion)
   - Search (Binary Search, BFS, DFS)
3. **Complexity Analysis:**
   - Big O, Ω, Θ
4. **String Manipulation:**
   - Palindromes, Anagrams, Substrings
5. **Graphs:**
   - DFS, BFS, articulation points, connected components
6. **Logic Simulation:**
   - Turn-based problems, pattern generation

---

## 🧠 8. Key Takeaways

- Focus on **clarity**, not just correctness — Booking.com values readable, well-structured code.
- **Comment your reasoning** during problem-solving.
- Emphasize **time and space efficiency** — explain complexity if asked.
- **Practice common problems** on platforms like *HackerRank*, *LeetCode*, and *GeeksForGeeks*.

---

**Author:** _Prepared by ChatGPT (GPT‑5) for Booking.com Candidate Readiness_  
**Format:** Markdown (.md) — ready for GitHub README-style presentation
