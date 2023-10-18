
# Minesweeper Game

![image](https://github.com/jgcoelhof/toDoList/assets/95655454/7aa45fdf-6463-463f-9340-d7a5b34ca787)
## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [How to Play](#how-to-play)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This is a Python implementation of the classic Minesweeper game. It's a single-player puzzle game where the objective is to clear a rectangular board containing hidden mines without detonating any of them. The game has various difficulty levels, including easy, medium, and hard, to challenge players of all skill levels.

## Features

- Classic Minesweeper gameplay.
- Customizable board size and mine density.
- Colorful art for a visually pleasing experience.
- Mine counter.

## How to Play

1. **Objective:** The goal of Minesweeper is to clear the board without detonating any mines.

2. **Rules:**
   - Left-click on a cell to reveal it. If it's a mine, you lose.
   - Right-click on a cell to mark it as a potential mine.
   - The numbers on revealed cells indicate how many mines are adjacent.

3. **Winning:** To win, reveal all non-mine cells. The timer will track your progress.

4. **Losing:** If you reveal a mine, the game ends. You can restart or exit.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/jgcoelhof/campo_minado.git
   cd campo_minado
   ```

2. Create a Python virtual environment (recommended):

   ```shell
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. Install the required dependencies:

   ```shell
   pip install -r requirements.txt
   ```

## Usage

To start the game, run the following command:

```shell
python campo_minado.py
```

Follow the on-screen instructions to play the game.


---

