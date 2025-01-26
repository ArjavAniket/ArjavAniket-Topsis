
# Topsis-Arjav-102203111

**Topsis-Arjav-102203111** is a Python package designed for implementing the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) method. This technique is widely used in multi-criteria decision-making scenarios, allowing users to rank alternatives effectively based on several criteria. The package offers both programmatic and command-line interface (CLI) usage, making it user-friendly and versatile. Additionally, it provides functionality to process decision matrices in CSV files seamlessly.

---

## Installation

You can install the package directly from PyPI using the following command:

```bash
pip install Topsis-Arjav-102203111
```

---

## Usage

### CLI Usage

Once installed, you can use the package via the command line. The general syntax for the CLI is as follows:

```bash
topsis <input_file> <weights> <impacts> <output_file>
```

- **`input_file`**: Path to a CSV file containing the decision matrix (rows represent alternatives, columns represent criteria).
- **`weights`**: Comma-separated values representing the weight of each criterion (e.g., `1,2,3,4`).
- **`impacts`**: Comma-separated signs (`+` for benefit and `-` for cost) indicating the impact of each criterion (e.g., `+,+,-,+`).
- **`output_file`**: Path to save the results, including rankings.

#### Example:

Suppose you have a decision matrix stored in `input.csv`, and you want to assign equal weights to all criteria and define the impacts as benefit, benefit, cost, and benefit. You can execute the following command:

```bash
topsis input.csv "1,1,1,1" "+,+,-,+" output.csv
```

---

## Features

- **Efficient Multi-Criteria Decision Making**: Implements the TOPSIS methodology to compute rankings based on proximity to ideal solutions.
- **Command-Line Interface**: Provides a straightforward CLI for processing decision matrices and obtaining rankings.
- **Support for CSV Files**: Effortlessly handles CSV input and output for ease of use.

---

## Requirements

To run this package, ensure the following dependencies are installed:

- **Python**: Version 3.6 or higher  
- **Numpy**: Version 1.21.0 or higher  
- **Pandas**: Version 1.3.0 or higher  

---

## License

This project is distributed under the MIT License. Refer to the LICENSE file for more information.

---

## Author

Developed and maintained by **Arjav Aniket**.  

Feel free to reach out for feedback or queries:  
**Email**: arjavaniket@gmail.com  

---

### Contributing

Contributions are welcome! If you encounter any issues or wish to enhance the package, feel free to open an issue or submit a pull request on GitHub.

---

### Disclaimer

This package is developed for educational purposes and should be verified for accuracy before use in critical decision-making scenarios.
