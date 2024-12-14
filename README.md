# CS61A: Cats

This repository contains the implementation of the [Cats](https://cats.cs61a.org) project for UC Berkeley's CS61A course. Cats, short for Computer Aided Typing Software, typing speed game with singleplayer and multiplayer capabilities inspired by typeracer. It also features an autocorrect feature, which attempts to correct a misspelled word after it is typed.

## Project Overview

Cats offers users a prompt to type out. The program measures users' speed in words per minute, typing accuracy, and time taken to complete the prompt. The user can also use the autocorrect feature to correct words they have misspelled, or narrow down topics of interest to type about.

### Key Concepts

- **String Manipulation & Functional Programming:**: Processing typed text input and using recursion.
- **Typing Test Logic & Performance Metrics:**: Calculating typing accuracy and uploading progress to a multiplayer server.

## Repository Structure

```
cs61a-cats/
├── cats.py          # Main logic
├── score.py         # Accuracy checking
├── cats_gui.py      # Graphical User Interface for playing Cats
├── tests/           # Directory containing test files
├── data/            # Sample words
└── README.md        # Project overview and instructions (this file)
```

## Getting Started

### Prerequisites

To run the project, you'll need Python 3.6 or later. Install it from the [official Python website](https://www.python.org/downloads/).

### Installation

Clone the repository:

```bash
git clone https://github.com/matthewtridoan/cs61a-cats.git
cd cs61a-cats
```

### Running the Game

To use Cats with the graphical interface:

```bash
python cats_gui.py
```

## Contributing

Contributions are welcome! If you'd like to make changes or improvements, feel free to fork the repository, make your changes, and submit a pull request.

## Acknowledgments

- **UC Berkeley CS61A Team**: For creating this fantastic project.
- **John DeNero**: Instructor of CS61A, whose materials inspired this implementation.
- [CS61A Official Website](https://cs61a.org/): Course resources and materials.
