# One Rule Algorithm

This repository contains an implementation of the One Rule (1R) algorithm, a simple yet effective machine learning algorithm for generating decision rules based on a single attribute. The implementation is designed for educational purposes and was developed during the Machine Learning class at UNIVESP.

## Features

- **Rule Generation**: Automatically generates decision rules for a dataset based on attributes and their values.
- **Error Rate Calculation**: Computes error rates for each attribute to determine the best attribute for decision-making.
- **Dataset Support**: Includes a sample dataset (`one-rule.csv`) for testing and demonstration purposes.
- **Notebook Integration**: Provides a Jupyter Notebook (`one-rule.ipynb`) for interactive exploration and execution.

## Repository Structure

- `data/`: Contains the sample dataset used for the algorithm.
  - `one-rule.csv`: A CSV file with weather data and a target column (`play`) for classification.
- `notebook/`: Includes the Jupyter Notebook for interactive execution.
  - `one-rule.ipynb`: A notebook demonstrating the implementation and usage of the One Rule algorithm.
- `README.md`: This file, providing an overview of the repository.

## Usage

1. **Dataset**: The dataset (`one-rule.csv`) contains weather attributes (`outlook`, `temperature`, `humidity`, `wind`) and a target column (`play`) indicating whether to play or not.
2. **Notebook**: Open the `notebook/one-rule.ipynb` file in Jupyter Notebook to explore the implementation and run the algorithm step-by-step.
3. **Execution**: The notebook demonstrates how to load the dataset, count occurrences, generate rules, and display results.

## Example Output

The algorithm generates decision rules for each attribute, calculates error rates, and identifies the best attribute with the lowest error rate. Example output includes:

- Generated rules for each attribute.
- Error rates for each attribute.
- The best attribute and its associated rules.

## Requirements

- Python 3.12.7
- Pandas library
- Jupyter Notebook (optional, for running the notebook)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/one-rule-algorithm.git
   cd one-rule-algorithm
   ```
2. Install dependencies:
   ```bash
   pip install pandas
   ```
3. Run the notebook:
   ```bash
   jupyter notebook notebook/one-rule.ipynb
   ```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

This implementation was developed as part of the Machine Learning class at UNIVESP.

