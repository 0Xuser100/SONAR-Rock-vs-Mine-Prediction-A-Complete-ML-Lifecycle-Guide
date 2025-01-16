# SONAR Rock vs Mine Prediction

This project focuses on classifying SONAR signals to distinguish between **Rocks (R)** and **Mines (M)** using machine learning techniques. The dataset contains 208 samples, each with 60 features representing the energy levels of sonar signals at different frequencies.
# README


## Kaggle Notebook
Explore the detailed implementation of my project in this Kaggle Notebook:
[Sonar Rock vs Mine Prediction: A Complete ML Lifecycle](https://www.kaggle.com/code/triblex/sonar-rock-vs-mine-prediction-a-complete-ml-lifec)

## Kaggle Dataset
Access the dataset that i publish on kaggle:
[Underwater Sonar Signals: Rocks and Mines Dataset](https://www.kaggle.com/datasets/triblex/underwater-sonar-signals-rocks-and-mines-dataset)


## Table of Contents
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Dataset
The dataset is available in the `data` folder and can also be downloaded from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks)).

- **Number of Instances**: 208
- **Number of Features**: 60
- **Target Variable**: Binary (`R` for Rock, `M` for Mine)
- **Missing Values**: None

## Project Structure
```
sonar-rock-vs-mine/
├── data/
│   └── sonar_data.csv          # Dataset file
├── notebooks/
│   └── sonar_rock_vs_mine.ipynb # Jupyter Notebook
├── models/
│   └── sonar_rf_model.pkl      # Trained Random Forest model
├── requirements.txt            # Python dependencies
├── README.md                   # Project overview
└── LICENSE                     # License file
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/0Xuser100/SONAR-Rock-vs-Mine-Prediction-A-Complete-ML-Lifecycle-Guide.git
   cd SONAR-Rock-vs-Mine-Prediction-A-Complete-ML-Lifecycle-Guide
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/sonar_rock_vs_mine.ipynb
   ```

## Usage
- Run the notebook to preprocess the data, train machine learning models, and evaluate their performance.
- The trained model is saved in the `models` folder and can be loaded for predictions.

## Results
The best-performing model achieved an accuracy of **97.1%** on the test set. For detailed results, refer to the notebook.

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Dataset Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks))
- Original Authors: R. P. Gorman and T. J. Sejnowski

---

## Author
**Mahmoud Abdelhamid**  

- **Skills**: Machine Learning, Deep Learning, Data Science, Competitive Programming  
- **Contact**: [LinkedIn](https://linkedin.com/in/mahmoud-abdelhamid) | [GitHub](https://github.com/0Xuser100)  

For any inquiries or collaboration opportunities, feel free to reach out!
