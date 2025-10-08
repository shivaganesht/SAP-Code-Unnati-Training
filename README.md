# SAP-Code-Unnati-Training-Notes

Welcome to my SAP Code Unnati Training repository! This repository contains Python exercises and learning materials from my SAP Code Unnati- **Dates:** October 7-8, 2025
- **Program:** SAP Code Unnati Training - Python Fundamentals & Data Preprocessing
- **Session Type:** Class Trainingaining class at **KPRIT College** conducted on **October 7, 2025**.

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

- **`8-10-25.ipynb`** - Data Preprocessing fundamentals covering:
  - **NumPy Introduction** - Scientific computing library basics
  - **Array Creation** - Different methods to create NumPy arrays (`np.array`, `np.asarray`)
  - **Data Types** - Understanding NumPy data types vs Python lists
  - **Multi-dimensional Arrays** - 1D, 2D, and 3D array operations
  - **Array Dimensions** - Working with `ndim` property and `reshape()` methods
  - **File I/O Operations** - Multiple formats (`.npy`, `.txt` with `savetxt/loadtxt`)
  - **Array Indexing** - Advanced indexing techniques for 1D, 2D, and 3D arrays
  - **Array Slicing** - Extracting subarrays using slice notation
  - **Structured Arrays** - Creating complex data structures with mixed data types
  - **Broadcasting** - Mathematical operations on arrays (covered conceptually)
  - **Pandas Introduction** - Data manipulation library fundamentals
  - **Pandas Series** - Creating and working with Series objects

### Trainer Resources
- **`Files From Trainer/`** - Professional training materials and examples:
  - `e1_pythonbaics.ipynb` - Python basics from instructor
  - `e3_numpypandas.ipynb` - NumPy and Pandas examples
  - `e5_data m(1).ipynb` - Advanced data manipulation techniques
  - `1725628504-Data Manipulation Using Pandas Library (1).ipynb` - Comprehensive Pandas guide

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

**NumPy Data Processing:**
```python
# Multi-dimensional array operations
arr = np.arange(12).reshape(3,4)  # Creates 3x4 matrix
print(arr[1,2])  # Element at row 1, column 2

# Structured arrays for complex data
person_data = np.array([('Shiva Ganesh', 22, 21.0)],
                      dtype=[('Name', (np.str_, 10)), ('Age', np.int32), ('Weight', np.float64)])
```

**Pandas Series Operations:**
```python
# Creating pandas Series with mixed data types
import pandas as pd
data = np.array([11, 12, 13, 14, 'mohan'])
ser = pd.Series(data)  # Handles mixed data automatically
print(ser)  # Output shows indexed series with mixed types
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
- **NumPy Mastery**: Scientific computing and array operations
- **Data Structure Design**: Structured arrays for complex data types
- **File I/O Operations**: Multiple data persistence formats
- **Array Indexing & Slicing**: Advanced data access techniques
- **Pandas Fundamentals**: Data manipulation and Series creation
- **Professional Training Resources**: Access to instructor materials

## 🏫 Training Details

- **Institution:** KPRIT College
- **Date:** October 7, 2025
- **Program:** SAP Code Unnati Training
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
- [x] **Data Preprocessing - NumPy Fundamentals** 📊
  - [x] NumPy library introduction and setup
  - [x] Array creation and data type understanding
  - [x] Multi-dimensional array operations (1D, 2D, 3D)
  - [x] Array dimension properties and `reshape()` methods
  - [x] **File I/O Operations** - Multiple formats (`.npy`, `.txt`)
  - [x] **Advanced Array Indexing** - 1D, 2D, and 3D indexing techniques
  - [x] **Array Slicing** - Extracting subarrays and data subsets
  - [x] **Structured Arrays** - Mixed data types and complex structures
  - [x] **Broadcasting Concepts** - Mathematical operations overview
  - [x] **Complete NumPy Mastery** 🎯
  - [x] **Pandas Introduction** - Data manipulation library setup
  - [x] **Pandas Series Creation** - Basic Series objects and data types
  - [ ] Advanced Pandas operations (in progress)
  - [ ] DataFrame operations (upcoming)

## 🤝 Contributing

This is a personal learning repository, but feel free to:
- Report issues
- Suggest improvements
- Share learning resources

## 📧 Contact

If you have any questions about this training material, feel free to reach out or open issues!

---
*Last updated: October 8, 2025*

**Repository Stats:**
- Language: Python & NumPy
- Training Program: SAP Code Unnati at KPRIT College
- Training Dates: October 7-8, 2025
- Focus: Data Preprocessing with NumPy (In Progress)
- Completed: Python Functions & Parameter Types
- Next Topic: Advanced NumPy & Pandas
