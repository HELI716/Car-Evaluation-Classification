# Car Evaluation Analysis

This project involves analyzing a dataset of car evaluations to predict their acceptability based on various attributes. The dataset contains information on buying price, maintenance cost, number of doors, capacity in terms of persons, size of luggage boot, and estimated safety of the car.

## Project Structure

The project includes the following files:
- `car_evaluation.csv`: Dataset containing car attributes and their acceptability.
- `car_evaluation_analysis.ipynb`: Jupyter notebook with the analysis.

## Requirements

The analysis requires Python and several packages which can be installed using the requirements.txt included in this repository. To install the dependencies, run:

```bash
pip install -r requirements.txt
```

## Analysis Workflow

1. **Data Loading:** Load the car evaluations from `car_evaluation.csv`.
2. **Data Preprocessing:** Convert categorical variables into numeric format using ordinal encoding.
3. **Model Building:** Build a decision tree classifier to predict the acceptability of cars.
4. **Model Evaluation:** Evaluate the model using accuracy score.

## Usage

To run the analysis, open the `car_evaluation_analysis.ipynb` in Jupyter Notebook or JupyterLab and execute the cells sequentially.

## Contributing

Contributions to this project are welcome. You can help by:
- Improving the existing model.
- Adding new models to compare performance.
- Enhancing the data preprocessing step.
