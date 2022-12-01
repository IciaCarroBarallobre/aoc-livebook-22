# Advent of code (AOC) 2022 & Livebook 🤶

Hey! I will solve the advent of code (AOC) using Elixir 💧 &amp; Livebook 📚. 

📖 In this livebook are indexed all puzzles completed and their answers: [AOC Index Livebook](./AdventOfCodeIndex.livemd).

[![Run in Livebook](https://livebook.dev/badge/v1/pink.svg)](https://livebook.dev/run?url=https://github.com/IciaCarroBarallobre/aoc-livebook-22/blob/main/AdventOfCodeIndex.livemd)

🚢 Be careful about the port! Maybe, it's in use.


**Index**
* [Basic Concepts](#basic-concepts)
* [Project Structure](#project-structure)
* [Project Installation](#project-installation)


## Basic concepts

- 📅 [Advent of Code](https://adventofcode.com/2022) is an advent calendar of **small programming puzzles** for a variety of skill sets and skill levels that can be solved in any programming language you like. 

- 📖 [Livebook](https://livebook.dev/) is a web application for writing interactive and collaborative code notebooks. 

## Project Structure

```python

|   "README.md"                  <-- # This file: Introduction and abstract of the project, including installation steps.
|   "AdventOfCodeIndex.livemd"   <-- # AOC index to the different puzzles.
|   "MoreInfo.md"
|   .gitignore                   <-- # File placed in the repository that tells git not to track certain files.
|   
\---Puzzles
    +---Day1             
    |       "Day1.livemd"
    ...    
    |
    |       
    \---DayX
```

(Made with: `tree /f /a > tree.txt`)

## Project Installation 

📚 If you want to use Livebook: 

* Step 1: Install and configure Git ([Install path](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)) with GitHub ([How to configure GitHub](https://docs.github.com/en/get-started/quickstart/set-up-git)).
* Step 2: Install [Elixir](https://elixir-lang.org/install.html).
* Step 3: Install [Livebook](https://livebook.dev/#install).
* Step 4: Download the project with GitHub Desktop, by https or by ssh. For example with https:

```shell
git clone https://github.com/IciaCarroBarallobre/aoc-livebook-22.git
```

* Step 6: Initialize Livebook and search the file: AdventOfCodeIndex.livemd
