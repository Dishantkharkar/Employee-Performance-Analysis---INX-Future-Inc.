# Employee Performance Analysis for INX Future Inc.

This repository contains a data science project focused on analyzing and improving employee performance at INX Future Inc, a leading data analytics and automation solutions provider. The project aims to provide actionable insights into employee performance and recommendations to enhance it while maintaining a positive work environment.

## Project Structure

- **Project Summary**:
  - **Requirement**: Data from third-party sources.
  - **Analysis**: Interpreting data and summary of various choices, from selecting machine learning algorithms to data processing techniques.
  - **Summary**: Project summary with analysis and recommendations.

- **data**:
  - **external**: Data from third-party sources.
  - **processed**: The final, canonical data sets for modeling.
  - **raw**: The original, immutable data dump.

- **src**:
  - **Data Processing**: Jupyter notebooks for data processing, data munging, and exploratory analysis.
    - `data_processing.ipynb`
    - `data_exploratory_analysis.ipynb`
  - **models**: Scripts to train machine learning models and make predictions.
    - `train_model.ipynb`
    - `predict_model.ipynb`
  - **visualization**: Scripts for creating exploratory and results visualizations.
    - `visualize.ipynb`

- **references**: Data dictionaries, manuals, and explanatory materials.

## Getting Started

1. **Data**: Obtain the project data from [INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls](http://data.iabac.org/exam/p2/data/INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls) and place it in the appropriate data directories (external, processed, or raw) as needed.

2. **Data Processing**: Explore and process the data using the Jupyter notebooks provided in the `src/Data Processing` directory.

3. **Model Training**: Use the scripts in the `src/models` directory to train machine learning models based on the processed data.

4. **Predictions**: Run the `predict_model.ipynb` script to make predictions using the trained model.

5. **Visualization**: Generate visualizations using the `visualize.ipynb` script.

6. **Summary and Recommendations**: Refer to the `Project Summary/Summary` section for a comprehensive project summary with analysis and recommendations.

## Contributing

We welcome contributions to this project. If you have suggestions or improvements to share, please submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- We thank INX Future Inc for providing the data and supporting this analysis.
- The project structure was inspired by the best practices for organizing data science projects.
