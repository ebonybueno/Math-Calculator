# Math-Calculator

### Overview
A simple and interactive calculator developed using MakeCode Arcade, designed to engage students with a unique way to approach math in the classroom.

### Motivation
This project aims to provide students with a hands-on approach to learning math through an interactive calculator. It encourages exploration and helps students understand math in an engaging digital format.

### Features
- Basic calculator functions (addition, subtraction, multiplication, division)
- User-friendly interface for students of various age groups
- Built on MakeCode Arcade for accessibility and simplicity

### Table of Contents
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Technologies] (#technologies)
- [Code Example](#code-example)
- [Project Status](#project-status) 
- [Credits](#credits)

### Installation
1. Visit the MakeCode Arcade website: [MakeCode Arcade][(https://ebonybueno.github.io/calculator/)]
2. Import the project using the provided GitHub repository link or .hex file.
3. Run the calculator on your preferred device or simulator.

### How to Use
1. Launch the calculator and input numbers using the arrow keys.
2. Select operations (e.g., `+`, `-`, `*`, `/`) by navigating the options and pressing enter.
3. Results display automatically after each calculation.

## Technologies 
- Platform: MakeCode Arcade  
- Language: Python/MakeCode Blocks  

## Setup  
1. Access [MakeCode Arcade](https://arcade.makecode.com/).  
2. Import the calculator code into the editor.  
3. Run the simulator to interact with the calculator.  

## Code Example 
```python
game.splash("What two numbers would you like to add?")
FirstNumber = game.ask_for_number("")
SecondNumber = game.ask_for_number("")
game.splash("" + str(FirstNumber) + " + " + str(SecondNumber) + " = " + str(FirstNumber + SecondNumber))
```
## Project Status  
This project is in prototype phase, designed for educational purposes.

### Credits
Developed by [Ebony Bueno](https://github.com/ebonybueno) as part of a learning project to explore coding in educational tools.
