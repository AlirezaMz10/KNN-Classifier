# KNN Classifier

This repository contains a Python implementation of the **K-Nearest Neighbors (KNN)** algorithm. The project classifies data points based on their nearest neighbors using a custom implementation. It uses the `iris.csv` dataset for testing and visualization.

## Features
- Calculates distances between data points.
- Implements the KNN algorithm from scratch.
- Visualizes classifier performance for different values of `k`.

## Dataset
The dataset used in this project is `iris.csv`. Ensure the file is placed in the root directory of the project before running the script.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AlirezaMz10/KNN-Classifier.git
   ```
2. Navigate to the directory:
   ```bash
   cd KNN-Classifier
   ```


## Usage

1. Open the script file `knn_classifier.py` in your preferred Python IDE or editor.
2. Ensure the dataset `iris.csv` is present in the same directory as the script.
3. Run the script:
   ```bash
   python knn_classifier.py
   ```

The script will calculate predictions for different values of `k` and plot a graph of the accuracy for each `k` value.

## Libraries Used
- `numpy`: For numerical calculations.
- `matplotlib`: For data visualization.

## Visualization
The program plots the performance of the classifier for various values of `k` using a line graph. This helps determine the optimal `k` value for the classifier.

## Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The `iris.csv` dataset used in this project is widely recognized for machine learning examples.
- Special thanks to the open-source community for the tools and resources used in this project.

