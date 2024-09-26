# Spotify Most Streamed Songs Analysis

This project analyzes data on the most streamed songs on Spotify using machine learning techniques, such as XGBoost.

## Project Structure
- `data/`: contains the CSV file with the most streamed songs data.
- `notebooks/`: contains the Jupyter Notebook with the analysis and model training.
- `models/`: contains the trained model saved in `.pkl` format.

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/CesarRonai/Spotify-Most-Streamed-Songs-Analysis
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook notebooks/SpotifyProject.ipynb
    ```

## Results
After training the XGBoost model, the best performance was:

- **Test R²**: 0.740

## Dependencies
The project requires the following Python libraries, which can be installed via `pip` using the `requirements.txt` file:

- pandas
- numpy
- xgboost
- scikit-learn
- matplotlib
- seaborn

## License
Include a license here, such as MIT, if applicable.
