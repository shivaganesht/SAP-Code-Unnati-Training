# SAP-Code-Unnati-Training-Notes

Welcome to my SAP Training repository! This repository contains Python exercises and learning materials from my SAP training class at **KPRIT College** conducted on **October 7, 2025**.

## 📚 Contents

### Notebooks
- **`7-10-25.ipynb`** - Comprehensive Python programming exercises covering:
  - **Positional Arguments** - Basic function definitions with required parameters
  - **Keyword Arguments** - Functions with named parameters
  - **Default Parameters** - Functions with optional arguments and default values
  - **Variable Length Arguments (*args)** - Functions accepting multiple positional arguments
  - **Keyword Variable-Length Arguments (**kwargs)** - Functions accepting multiple keyword arguments
  - **Mixing Different Argument Types** - Advanced combination of all argument types
  - **Card Game Implementation** - Practical application using random module
  - String manipulation and input handling
  - Tuple operations and data structures
  - Mathematical calculations and return values

## 🐍 Python Exercises Covered

### 1. Positional Arguments
- `print_name(str)` - Creates a welcome tuple with user's name
- `name()` - Gets user input and displays formatted welcome message
- `hello(n1, n2)` - Demonstrates function parameter passing
- `find_square(num)` - Mathematical function with single parameter

### 2. Keyword Arguments
- `greet(name, message)` - Function with named parameters for flexible calling
- `archana(gotram, name1, name2, name3, name4)` - Multiple parameter function with user input

### 3. Default Parameters
- `greet(first_name, last_name='Doe')` - Function with optional parameters
- `dream_company(Package, Company='Microsoft')` - Professional example with default values

### 4. Variable Length Arguments (*args)
- `purchaseinfo(product1, *products)` - Function accepting multiple items
- Handles dynamic number of product purchases

### 5. Keyword Variable-Length Arguments (**kwargs)
- `print_info(**kwargs)` - Flexible function accepting any keyword arguments
- Real-world examples: product information and personal details
- Dynamic key-value pair processing

### 6. Mixing Different Argument Types
- `mixed_arguments(a, b=2, *args, **kwargs)` - Advanced function combining all argument types
- Demonstrates proper parameter order: positional → default → *args → **kwargs
- Real-world application showing comprehensive parameter handling

### 7. Practical Application - Card Game Implementation
- `new_deck()` - Creates a complete deck of 52 cards using list comprehension
- `draw_card(n, cards_list)` - Shuffles deck and draws n cards for players
- **Random Module Integration** - Uses `random.shuffle()` for card randomization
- **List Comprehension** - Efficient deck creation with nested loops
- **Real Game Logic** - Simulates card distribution between multiple players

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or VS Code with Python extension

### Running the Code
1. Clone this repository
```bash
git clone https://github.com/shivaganesht/SAP-Training.git
```

2. Navigate to the project directory
```bash
cd SAP-Training
```

3. Open the Jupyter notebook
```bash
jupyter notebook 7-10-25.ipynb
```
or open it in VS Code

4. Run the cells to execute the Python code

## 📝 Example Usage

The notebook demonstrates various function types:

**Positional Arguments:**
```python
find_square(2)  # Returns 4
```

**Keyword Arguments:**
```python
greet(message="Hello", name='Alice')  # "Hello, Alice!"
```

**Default Parameters:**
```python
dream_company('10 LPA')  # Uses default Company='Microsoft'
```

**Variable Length Arguments:**
```python
purchaseinfo('Laptop', 'Mouse', 'Keyboard', 'Monitor')  # Handles multiple items
```

**Keyword Variable-Length Arguments:**
```python
print_info(name="Samsung Watch", price="45000", warranty="2 years")  # Flexible key-value pairs
```

**Mixing Different Argument Types:**
```python
mixed_arguments(1, 3, 4, 5, x=10, y=20)  # Combines all argument types
# Output: a: 1, b: 3, args: (4, 5), kwargs: {'x': 10, 'y': 20}
```

**Card Game Implementation:**
```python
cards_list = new_deck()  # Creates 52-card deck
hand1 = draw_card(5, cards_list)  # Draws 5 random cards
# Output: Hand1= ['7C', 'KH', '3D', 'AS', '9S']
```

## 🎯 Learning Objectives

- **Function Parameter Types**: Master all Python argument types
- **Positional Arguments**: Required parameters in specific order
- **Keyword Arguments**: Named parameters for flexible function calls
- **Default Parameters**: Optional arguments with fallback values
- **Variable Length Arguments (*args)**: Handle dynamic number of inputs
- **Keyword Variable-Length Arguments (**kwargs)**: Process flexible key-value pairs
- **Mixing Different Argument Types**: Advanced combination of all parameter types
- **Parameter Order Rules**: Understanding proper function signature structure
- **Random Module**: Working with `random.shuffle()` for randomization
- **List Comprehension**: Efficient data structure creation with nested loops
- **Practical Applications**: Real-world game logic and card distribution systems
- **Input/Output Operations**: User interaction with `input()` and formatted output
- **Data Structures**: Tuples, dictionaries, lists, and string manipulation
- **Algorithm Implementation**: Card shuffling and dealing mechanisms

## 🏫 Training Details

- **Institution:** KPRIT College
- **Date:** October 7, 2025
- **Program:** SAP Training - Python Fundamentals
- **Session Type:** Class Training

## 📊 Training Progress

- [x] **Positional Arguments** - Basic function parameters
- [x] **Keyword Arguments** - Named parameter functions
- [x] **Default Parameters** - Optional arguments with defaults
- [x] **Variable Length Arguments (*args)** - Dynamic positional parameters
- [x] **Keyword Variable-Length Arguments (**kwargs)** - Dynamic keyword parameters
- [x] **Mixing Different Argument Types** - Advanced parameter combinations
- [x] **Parameter Order Rules** - Proper function signature structure
- [x] Input/Output operations with user interaction
- [x] Tuple and data structure manipulation
- [x] Mathematical functions and calculations
- [x] Real-world function applications
- [x] **Card Game Implementation** - Practical programming project
- [x] **Random Module Usage** - Randomization and shuffling algorithms
- [x] **List Comprehension** - Advanced data structure creation
- [x] **Game Logic Development** - Multi-player card distribution
- [x] Complete Python Function Mastery 🎉
- [x] Practical Programming Applications 🎮
- [ ] Data Preprocessing (upcoming)

## 🤝 Contributing

This is a personal learning repository, but feel free to:
- Report issues
- Suggest improvements
- Share learning resources

## 📧 Contact

If you have any questions about this training material, feel free to reach out or open issues!

---
*Last updated: October 7, 2025*

**Repository Stats:**
- Language: Python
- Training Program: SAP at KPRIT College
- Training Date: October 7, 2025
- Focus: Python Functions & Parameter Types (Complete)
- Next Topic: Data Preprocessing
