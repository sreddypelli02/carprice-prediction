# Car Price Prediction

This is a machine learning project that predicts car prices based on various features using a Random Forest Regressor model. The app uses data from `cardata.csv` to train the model and predicts car prices based on user inputs.

## Files in the Project

- **main.py**: Main script that handles data preprocessing, model training, and prediction logic.
- **app.py**: Flask application that serves the car price prediction model through a web interface.
- **cardata.csv**: Dataset containing various features of cars, used for training the model.
- **templates/index.html**: HTML file for the web interface, where users can input car details to predict the price.
- **random_forest_regressor.pkl**: Pickled model file for the trained Random Forest Regressor.
- **requirements.txt**: List of Python dependencies needed to run the project.
- **untitled.ipynb**: Jupyter Notebook that may contain exploratory analysis or additional work.
- **.ipynb_checkpoints**: Contains checkpoint files for Jupyter Notebook.

## Setup

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/repository-name.git
    ```

2. Navigate to the project directory:
    ```bash
    cd carprice
    ```

3. Create and activate a virtual environment (if using `conda` or `venv`):
    ```bash
    conda create --name carprice python=3.8
    conda activate carprice
    ```

4. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Run the Flask app:
    ```bash
    python app.py
    ```

6. Open the web browser and go to:
    ```
    http://127.0.0.1:5000
    ```

## Model

The car price prediction is powered by a Random Forest Regressor, which is a machine learning algorithm that works well for regression tasks. The model has been trained on a dataset of car details, including features such as make, model, year, mileage, and more.

The model is saved as a pickled file `random_forest_regressor.pkl`, and it is loaded into the app for predictions.

