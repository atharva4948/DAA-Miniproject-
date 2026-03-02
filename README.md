# DAA-Miniproject-

⚡ Performance Comparison: Merge Sort vs Multithreaded Merge Sort (Python)

This project implements and compares the performance of a standard Merge Sort algorithm and a multithreaded version using Python’s threading module. The goal is to analyze how parallel execution impacts sorting efficiency for different input sizes.

🔍 Project Overview

Two sorting approaches are implemented:

Standard Merge Sort

Recursive divide-and-conquer algorithm

Time complexity: O(n log n)

Deterministic and stable sorting

Multithreaded Merge Sort

Uses Python threads to sort left and right halves in parallel

Threads are synchronized using join() before merging

Designed to test performance improvement through parallelism

⚙️ Implementation Details

Random arrays generated using random.randint()

Tested on multiple input sizes:
1000, 5000, 10000, 50000, 100000

Execution time measured using time.time()

Results printed for direct runtime comparison

📊 Objective

To evaluate:

Practical performance differences

Overhead introduced by threading

Scalability behavior as input size increases

🎯 Key Concepts Demonstrated

Divide and conquer algorithms

Recursion

Multithreading in Python

Performance benchmarking

Time complexity analysis
