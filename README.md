# AlgoCypher - Cryptography Learning & Gaming Platform

![AlgoCypher](https://img.shields.io/badge/Language-Python-blue) ![GUI](https://img.shields.io/badge/GUI-CustomTkinter-green) ![Database](https://img.shields.io/badge/Database-SQL%20Server-red)

## 📚 Overview

**AlgoCypher** is an interactive cryptography learning platform that combines educational cipher algorithms with engaging game-based challenges. It's designed to teach users about various encryption and decryption techniques through practical implementation and real-time challenges with scoring systems.

## 🎮 Video Explanation

For a detailed walkthrough and visual explanation of the project, watch this video:
[![AlgoCypher Project Explanation](https://img.shields.io/badge/YouTube-Watch%20Video-red)](https://youtu.be/S9fDUpTTqjk?si=ArIBL7i9KBsbUlnm)

[Direct Link: https://youtu.be/S9fDUpTTqjk?si=ArIBL7i9KBsbUlnm](https://youtu.be/S9fDUpTTqjk?si=ArIBL7i9KBsbUlnm)

## 📋 Project Structure

### Core Files

#### 1. **Cyphers.py** - Cipher Algorithms Library
The main cryptographic algorithms implementation featuring:

**Classical Ciphers:**
- **Caesar Cipher** - Shift-based substitution cipher
- **ROT13** - Special case of Caesar cipher with fixed shift of 13
- **Reverse Cipher** - Reverses the entire text
- **Vigenere Cipher** - Polyalphabetic substitution using a keyword
- **Playfair Cipher** - Digraph substitution cipher
- **Rail Fence Cipher** - Transposition cipher using multiple rails

**Advanced Ciphers:**
- **Substitution Cipher** - General substitution with custom key mapping
- **Hill Cipher** - Mathematical cipher using linear algebra (matrix operations)
- **XOR Cipher** - Bitwise XOR operation with a key
- **Transposition Cipher** - Rearranges plaintext positions

**Specialized Ciphers:**
- **Egyptian Hieroglyph Cipher** - Combines Caesar-Fibonacci shift with Egyptian hieroglyph symbols
- **Delta Cipher (ΔCipher)** - Mathematical encryption using calculus (derivatives and integrals) with symbolic computation
- **Caesar-Fibonacci** - Position-based cipher using Fibonacci sequence

#### 2. **Dashboard_game.py** - Main Gaming Interface
Interactive game dashboard with:
- **Multi-Level Challenges** - Three progressive difficulty levels
- **Row Transposition Cipher** - Level One cipher challenge
- **Complex Cipher Challenges** - Levels Two and Three
- **Leaderboard System** - Track top players and scores
- **Real-Time Timer** - 120-second challenges with countdown
- **Database Integration** - SQL Server connection for user data and scores
- **Scoring System** - Automatic score calculation and updates
- **User Authentication** - Connect to cyber_user database

#### 3. **Introduction_game.py** - Educational Challenges
Initial learning module featuring:
- **Fibonacci Encryption/Decryption** - Position-based Fibonacci shift
- **Hieroglyph Cipher Challenges** - Egyptian symbols with Fibonacci encryption
- **Round 5 Cipher** - Complex categorized cipher puzzle
- **Calculus Cipher Game** - Mathematical cipher using symbolic computation
- **Interactive GUI** - Neon-themed interface with Consolas font
- **Progress Tracking** - Real-time game state management

#### 4. **ImageEncryption.py** - Image-Based Cryptography
File encryption utility for images:
- **XOR Image Encryption** - Encrypt image files using XOR cipher with a custom key
- **Image Decryption** - Decrypt previously encrypted images
- **File Management** - Browse, select, and save encrypted/decrypted images
- **Supported Formats** - PNG, JPG, JPEG, BMP
- **User-Friendly GUI** - Dark-themed interface with file dialogs

## 🔐 Cipher Types Explained

### Substitution Ciphers
Replace each plaintext character with a ciphertext character consistently.
- Examples: Caesar, ROT13, Substitution, Playfair

### Transposition Ciphers
Rearrange plaintext characters without changing them.
- Examples: Rail Fence, Reverse, Row Transposition

### Polyalphabetic Ciphers
Use multiple substitution rules based on position.
- Examples: Vigenere, Fibonacci-Caesar

### Mathematical Ciphers
Use mathematical operations for encryption.
- Examples: Hill Cipher (matrices), Delta Cipher (calculus), XOR Cipher (bitwise)

### Specialized Ciphers
Unique implementations with specific characteristics.
- Examples: Egyptian Hieroglyph, Round 5 Cipher

## 🛠️ Technologies & Dependencies

### Core Libraries
- **Python 3.x** - Programming language
- **CustomTkinter** - Modern GUI framework
- **Tkinter** - GUI toolkit (built-in)
- **PIL (Pillow)** - Image processing
- **NumPy** - Numerical operations for Hill Cipher
- **SymPy** - Symbolic mathematics for Delta Cipher
- **PyODBC** - SQL Server database connection

### Database
- **SQL Server (MSSQL)** - User data and leaderboard storage
- **Database:** `cyber_user`
- **Tables:** Users, Scores, Leaderboard


## 📊 Game Features

### Challenge Modes
1. **Level One** - Row Transposition with 2-minute timer
2. **Level Two** - Advanced cipher challenges
3. **Level Three** - Complex multi-cipher puzzles
4. **Leaderboard** - Global ranking system

### User Interaction
- Select cipher challenges from main menu
- Input plaintext/ciphertext
- Real-time validation
- Score calculation and storage
- Database-backed leaderboard

### Visual Interface
- Dark theme with neon accents (green/cyan)
- Responsive layouts
- Timer display
- Score tracking
- Medal/achievement system

---

**Made with ❤️ for Cryptography Enthusiasts**

**Version:** 1.0  
**Last Updated:** 2025
