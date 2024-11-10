# pittsburgh-altitude-prediction-neural-network
Neural Network-Based Altitude Prediction and Stochastic Gradient Ascent for Peak Detection in Pittsburgh

This project demonstrates the use of a neural network to predict altitudes based on longitude and latitude for locations in Pittsburgh, and then identifies the highest peak using stochastic gradient ascent. The task involves training a model to predict altitudes across various locations, visualizing a contour map of Pittsburgh's terrain, and optimizing input coordinates to find the highest point.

## Project Structure

- **`pittsburgh_altitude_prediction.ipynb`**: Jupyter notebook containing all the code for training the neural network, visualizing the contour map, and performing gradient ascent to find the peak altitude.
- **`PittsburghMap.xls`**: Excel file containing data on longitude, latitude, and altitude for various locations in Pittsburgh.
- **`requirements.txt`**: Contains a list of Python dependencies required to run the code.

## Requirements

Before running the project, make sure you have the following Python packages installed:

- `numpy`
- `pandas`
- `torch`
- `matplotlib`
- `sklearn`

You can install these dependencies using `pip` by running the following command:

```bash
pip install -r requirements.txt

