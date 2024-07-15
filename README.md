# Tokenizing Program

This program demonstrates tokenization of words, phrases, and sentences based on user input. It provides interactive demos for each type of tokenization using C programming language.

## Table of Contents

- [Features](#features)
- [How to Use](#how-to-use)
- [Compilation](#compilation)
- [Usage Examples](#usage-examples)
- [Modules](#modules)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Tokenizing Words**: Input a series of words separated by spaces and see each word printed sequentially.
- **Tokenizing Phrases**: Input a series of phrases separated by commas and observe each phrase printed one by one.
- **Tokenizing Sentences**: Input a series of sentences separated by dots and view each sentence displayed in order.

## How to Use

To use the program, follow these steps:

1. **Compilation**:
   - Ensure you have a C compiler installed (e.g., GCC for Linux, MinGW for Windows).
   - Compile the program using the provided source code (`tokenizing.c` and `tokenizing.h`).

2. **Execution**:
   - Run the compiled executable.
   - Choose the "Tokenizing" module by entering `4` when prompted.
   - Follow the on-screen instructions to input words, phrases, or sentences.

3. **Interaction**:
   - Each demo continues until you enter `q` to quit.
   - The program will display each token (word, phrase, or sentence) sequentially as you input them.

## Compilation

### Linux (GCC)

```bash
gcc -o tokenizing tokenizing.c
