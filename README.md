Static Code Analyzer CLI
------------------------

### Overview

This project provides a command-line utility that analyzes Python code using an Abstract Syntax Tree (AST), caches the analysis results in a SQLite database, and tests API load with asynchronous concurrency. The tool is designed to be modular and easily extensible, with separate components for each core functionality.

### Architecture

- **src/core.py**: The core engine that handles AST analysis, caching, and concurrency testing.
- **src/cli.py**: A rich terminal interface that interacts with the user, imports and uses functions from the core.
- **tests/test_core.py**: Full pytest suite for testing the core functionalities.
- **requirements.txt**: A list of required Python packages.

### Installation

To install the tool, run:
```bash
pip install -r requirements.txt
```

### Usage

- **Analyzing Code**: `analyze-code <path-to-python-file>`
- **Concurrent Load Testing**: `test-concurrency <url> <number-of-requests>`

### Example

To analyze a Python file and cache the results:
```bash
$ analyze-code example.py
```

To test concurrent API load:
```bash
$ test-concurrency http://example.com/api/ 50
```

### Contributing

Contributions are welcome! Please refer to the contributing guidelines for details on how to get started.

### License

This project is licensed under the MIT License.

### Acknowledgments

Special thanks to the contributors and maintainers of the packages used in this project.

### Installation

To install the tool, run:
```bash
pip install -r requirements.txt
```

### Usage

- **Analyzing Code**: `analyze-code <path-to-python-file>`
- **Concurrent Load Testing**: `test-concurrency <url> <number-of-requests>`

### Example

To analyze a Python file and cache the results:
```bash
$ analyze-code example.py
```

To test concurrent API load:
```bash
$ test-concurrency http://example.com/api/ 50
```

### Contributing

Contributions are welcome! Please refer to the contributing guidelines for details on how to get started.

### License

This project is licensed under the MIT License.

### Acknowledgments

Special thanks to the contributors and maintainers of the packages used in this project.