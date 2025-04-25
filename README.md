# Used Car Evaluation

This project explores a dataset of used car sales to understand the factors that drive used car prices and provide recommendations to a used car dealership.

## Usage

1.  Clone the repository.
2.  Install the required libraries (pandas, numpy, matplotlib, seaborn, scikit-learn).
3.  Run the `prompt_II.ipynb` notebook to perform the analysis.

## Project Overview

This project utilizes the CRISP-DM framework to analyze a dataset of used car sales and identify key drivers of used car prices. The analysis includes data exploration, data quality assessment, feature engineering, and regression modeling.

### CRISP-DM Framework

The project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework. The first steps involve business understanding and data understanding.

### Business Understanding

The goal is to identify the key factors that influence used car prices to provide actionable insights to a used car dealership.

### Data Understanding

The dataset contains information on 426K used cars with 18 features, including:

*   `region`: The region the car is located in.
*   `price`: The listing price of the car.
*   `year`: The manufacturing year of the car.
*   `manufacturer`: The manufacturer of the car.
*   `model`: The model of the car.
*   `odometer`: The odometer reading of the car.
*   Other features like `condition`, `cylinders`, `fuel`, `transmission`, `drive`, `size`, `type`, and `paint_color`.

### Data Exploration and Quality Assessment

The data exploration process included:

1.  **Dataset Structure Analysis:** Examining the shape, data types, and sample data.
2.  **Data Quality Assessment:** Identifying missing values, outliers, and duplicate entries.

### Libraries Used

*   pandas
*   numpy
*   matplotlib
*   seaborn
*   scikit-learn

1.  Clone the repository.
2.  Install the dependencies.
3.  Run the main script.

## License

This project is licensed under the MIT License.

## Summary of Findings

The analysis of the used car dataset revealed several key factors that influence the price of a used car:

*   **Year:** Newer cars generally have higher prices.
*   **Odometer:** Cars with lower odometer readings tend to be more expensive.
*   **Condition:** Cars in excellent condition command higher prices.
*   **Transmission:** Automatic transmissions are generally more valued.

For a detailed exploration of the analysis, please refer to the [Used Car Evaluation Notebook](prompt_II.ipynb).

