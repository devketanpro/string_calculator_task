# string_calculator_task
Function to calculate sum of the numbers given inside a string with implementation of the test cases

## Features

- Returns 0 for an empty string.
- Returns the number for a single input.
- Sums up multiple comma-separated numbers.
- Treats new lines between numbers as commas.
- Supports custom delimiters specified as "//[delimiter]\\n[numbers]".
- Raises an exception for negative numbers, listing all found.

## Setup

### Prerequisites

- Python 3.x installed on your system.

### Installation

Clone the repository:

```bash
git clone <repository-url>
cd <repository-directory>
```
### Create Virtual Environment
```
python -m venv venv
```

### Activation on Windows
```
venv\Scripts\activate
```

### Activation on macOS/Linux
```
source venv/bin/activate
```

### Running Test Cases
```
python tests_string_calculator.py
```