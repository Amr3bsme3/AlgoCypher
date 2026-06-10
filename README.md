# AlgoCypher - Cryptography Learning & Gaming Platform

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square) ![GUI](https://img.shields.io/badge/CustomTkinter-GUI-green?style=flat-square) ![Database](https://img.shields.io/badge/SQL%20Server-Database-red?style=flat-square)

## Overview

**AlgoCypher** is an interactive cryptography platform that implements 11+ classical and advanced cipher algorithms with engaging game-based challenges. Users can encrypt/decrypt messages, solve timed cipher puzzles, and compete on a leaderboard.

**[▶️ Project Demo](https://youtu.be/S9fDUpTTqjk?si=ArIBL7i9KBsbUlnm)** | **[Video Explanation](https://www.youtube.com/watch?v=S9fDUpTTqjk)**

## Cipher Implementations

| Cipher Type | Implementation | Category |
|-------------|----------------|----------|
| **Caesar Cipher** | Character shift by fixed key | Substitution |
| **ROT13** | Caesar variant with fixed shift of 13 | Substitution |
| **Vigenere Cipher** | Polyalphabetic substitution with keyword | Polyalphabetic |
| **Playfair Cipher** | Digraph substitution using 5×5 matrix | Substitution |
| **Hill Cipher** | Matrix-based mathematical encryption | Mathematical |
| **Rail Fence Cipher** | Zigzag transposition across multiple rails | Transposition |
| **Substitution Cipher** | General character mapping with custom key | Substitution |
| **XOR Cipher** | Bitwise XOR operation with key | Mathematical |
| **Egyptian Hieroglyph** | Fibonacci-shift + hieroglyph symbols | Specialized |
| **Delta Cipher (ΔCipher)** | Calculus-based (derivatives & integrals) | Mathematical |
| **Caesar-Fibonacci** | Position-dependent Fibonacci sequence shift | Polyalphabetic |
| **Reverse Cipher** | Character reversal | Transposition |

## Modules Overview

**Cyphers.py** - Core cryptographic algorithms library with encryption/decryption functions for all 11+ ciphers and mathematical operations.

**Dashboard_game.py** - Main gaming interface with 3-level challenges, real-time timer (120 seconds per challenge), SQL Server leaderboard integration, and automatic score tracking.

**Introduction_game.py** - Educational learning module featuring Fibonacci encryption, hieroglyph puzzles, Round 5 cipher challenges, and calculus-based cipher games with neon UI.

**ImageEncryption.py** - XOR-based image encryption utility supporting PNG, JPG, JPEG, and BMP formats with file management and decryption capabilities.

## Key Features

- **11+ Cipher Algorithms** - Classical, mathematical, and specialized encryption methods
- **Interactive Gaming** - Three-level challenge progression with difficulty scaling
- **Real-Time Validation** - Immediate feedback on encryption/decryption attempts
- **Leaderboard System** - SQL Server-backed global ranking and score tracking
- **Image Encryption** - Dedicated XOR-based image file encryption/decryption
- **Educational Focus** - Learn cryptography through practical problem-solving
- **Modern UI** - Dark theme with neon accents, responsive design, real-time timers

## Architecture

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **GUI Framework** | CustomTkinter | Modern, responsive interface |
| **Image Processing** | PIL (Pillow) | Image encryption/decryption |
| **Mathematical Operations** | NumPy, SymPy | Hill Cipher, Delta Cipher, calculus-based encryption |
| **Database** | SQL Server | User data, scores, leaderboard |
| **Connection** | PyODBC | Database connectivity |
| **Language** | Python 3.x | Core implementation |

## Cipher Categories

- **Substitution** - Character replacement (Caesar, ROT13, Vigenere, Playfair)
- **Transposition** - Character rearrangement (Rail Fence, Reverse, Row Transposition)
- **Polyalphabetic** - Position-based substitution (Vigenere, Fibonacci-Caesar)
- **Mathematical** - Algorithmic encryption (Hill Cipher, Delta Cipher, XOR)
- **Specialized** - Unique implementations (Egyptian Hieroglyph, Round 5 Cipher)


## Challenge Structure

| Level | Challenge Type | Duration | Difficulty |
|-------|----------------|----------|-----------|
| **Level 1** | Row Transposition | 120 sec | Beginner |
| **Level 2** | Advanced Ciphers | 120 sec | Intermediate |
| **Level 3** | Multi-Cipher Puzzles | 120 sec | Advanced |
| **Leaderboard** | Global Ranking | - | All Levels |

## Learning Outcomes

Users gain practical knowledge in:
- **Cryptographic Principles** - Encrypt/decrypt using classical and modern algorithms
- **Cipher Analysis** - Understand strengths and weaknesses of different methods
- **Mathematical Encryption** - Matrix operations, calculus, and Fibonacci sequences
- **Software Security** - Real-world application of cryptography concepts
- **GUI & Database Integration** - Full-stack application development

---

**Version:** 1.0 | **Status:** Active Development  
For detailed walkthrough, see [Project Demo](https://youtu.be/S9fDUpTTqjk?si=ArIBL7i9KBsbUlnm)
