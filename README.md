# Indian GDP Prediction and Analysis (1980-2023)

This repository contains the code and resources for predicting and analyzing Indian Gross Domestic Product (GDP) from the year 1980 to 2023. The analysis is based on a dataset with 7 columns: Year, GDP(in Billion $ PPP), GDP Per capita (in Billion $ PPP),GDP per capita (in US$ nominal), GDP growth(real), Inflation rate (in Percent).

## Dataset

### Data Source
The dataset used in this project is sourced from https://en.wikipedia.org/wiki/Economy_of_India

### Data Description
- **Year**: The year for which the GDP data is recorded.
- **Per capita GDP**: The GDP per capita, which is the total GDP divided by the population.
- **Total GDP**: The total Gross Domestic Product of India for a specific year.
- **Growth rate**: The annual growth rate of the GDP.

## Dependencies

To run the code in this repository, you will need the following dependencies:

- Python 3.11.5
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

You can install these dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/indian-gdp-prediction.git
```

2. Navigate to the project directory:

```bash
cd indian-gdp-prediction
```

3. Run the Jupyter Notebook or Python script to perform analysis and prediction:

```bash
jupyter notebook Indian_GDP_Prediction.ipynb
```

or

```bash
python indian_gdp_prediction.py
```

## Analysis and Visualization

This project includes several visualizations to help you understand the Indian GDP data better. You can find these visualizations in the [visualization](./visualization) directory. Some of the key visualizations include:

1. **Line Plot**: Line chart showing the trend in Indian GDP over the years.
   
   ![Line Plot](./visualization/line_plot.png)

2. **Heatmap**: Heatmap showing the correlation between different GDP-related variables.

   ![Heatmap](./visualization/heatmap.png)

(Add more visualizations and descriptions as needed)

## Results

(Describe the results of your analysis and prediction here. Include any insights or conclusions you've drawn from the data.)

## Contributing

If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository on GitHub.
2. Clone your forked repository to your local machine.
3. Create a new branch for your feature or bug fix.
4. Make your changes and commit them with descriptive messages.
5. Push your changes to your GitHub fork.
6. Submit a pull request to the main repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to [insert names or organizations] for providing the dataset.
