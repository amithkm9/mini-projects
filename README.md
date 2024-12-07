Plagiarism Detection Tool
This repository contains a Python-based plagiarism detection tool that uses the Rabin-Karp Algorithm and fundamental concepts from Theory of Computation (ToC) to identify similarities between two text documents.

Features
Efficient String Matching: Leverages the Rabin-Karp algorithm for quick and accurate substring matching.
Customizable Parameters: Supports adjustable window size and similarity threshold.
Detailed Reporting: Provides a similarity ratio and highlights matching substrings.
Interactive File Upload: Built for use in Google Colab with file upload functionality.
How It Works
Hashing: The Rabin-Karp algorithm computes hash values for substrings, making string matching efficient.
Sliding Window: The tool slides a fixed-size window across the text, comparing substrings.
Plagiarism Detection: Calculates a similarity ratio and checks it against a configurable threshold.
Theory of Computation Concepts Used
This tool applies the following ToC principles:

Finite Automata: Simulates state transitions for substring processing.
Hash Functions: Models hashing as computational state transitions.
Complexity Theory: Optimizes performance with rolling hash computations.
Formal Languages: Matches substrings by checking membership in a language.
Decidability: Frames plagiarism detection as a Yes/No decision problem.
