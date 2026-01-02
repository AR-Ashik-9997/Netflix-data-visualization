# Netflix Data Visualization and Prediction

## Project Description

This project analyzes the Netflix titles dataset to gain insights into movies and TV shows available on the platform. It includes data cleaning, exploratory data analysis (EDA) with various visualizations, and machine learning models to predict the type of content (Movie or TV Show) based on the release year.

## Dataset

- **Source**: Kaggle Netflix Titles Dataset
- **File**: `Dataset/netflix_titles.csv`
- **Description**: Contains over 8,000 entries with details like title, type, director, cast, country, date added, release year, rating, duration, listed in, and description.

## Features

- **Data Cleaning**: Handling missing values, duplicates, and data type conversions.
- **Visualizations**:
  - Bar charts for content types
  - Pie charts for ratings
  - Histograms for movie durations
  - Scatter plots and line plots for trends over time
  - Top countries producing content
- **Machine Learning**:
  - Logistic Regression
  - Random Forest Classifier
  - Predicting content type using release year as the feature

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Installation

1. Clone or download the repository.
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook `Netflix Movies and Tv Shows.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
4. Run the cells sequentially.

## Project Structure

- `Netflix Movies and Tv Shows.ipynb`: Main analysis notebook
- `Dataset/netflix_titles.csv`: Dataset file
- `requirements.txt`: Python dependencies
- `all_in_one_subplot.png`: Saved visualization image

## Results

- Insights into Netflix's content strategy, including shifts from movies to TV shows.
- Machine learning models achieving high accuracy in content type prediction.

## License

This project is for educational purposes.
