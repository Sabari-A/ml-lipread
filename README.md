# Lip Reading(LipNet) using Deep Learning

This project focuses on lipreading using a deep learning model developed from scratch with reference to the LipNet Model, implemented using TensorFlow. The project includes a full-stack application created with Streamlit. Below is an overview of the project components:

## Installation

To install the required packages, run the following command:
```bash
pip install -r requirements.txt
```

## Lipreading Model Development

The lipreading model is developed in the `lipreading.ipynb` file. Here's a summary of the process:
- Data Acquisition: Data is downloaded from Google Drive.
- Data Pipeline: Creation of a data pipeline for preprocessing and feeding data into the model.
- Model Development: Building the deep learning model.
- Training: Training the model using the Connectionist Temporal Classification (CTC) loss function.
- Model Optimization: To save time, pre-trained weights are imported and utilized for testing.

## Full Stack Application

Before running the Streamlit app, ensure to download the trained model by following the instructions provided in the `lipreading.ipynb` file.

The lipreading application is implemented as a full-stack app using Streamlit. Key files include:
- `app.py`: Main application file located in the `app` folder.
- `modelutils.py`: Contains functions related to the model, also located in the `app` folder.
- `utils.py`: Utility functions used throughout the program.

## Usage

To utilize this project, follow these steps:
1. Clone this repository.
2. For model creation and training, run the `lipreading.ipynb` file.
3. Before running the Streamlit app, download the trained model as instructed in `lipreading.ipynb`.
4. For the full-stack Streamlit app, navigate to the `app` folder and run:
```bash
streamlit run app.py
```
This will launch the full-stack app.

## Demo

![Quick demo of the project](demo.mov)

## Acknowledgements

This project utilizes the following libraries:
- [TensorFlow](https://www.tensorflow.org/)
- [Streamlit](https://www.streamlit.io/)

## License

This project is licensed under the [The Unlicense](LICENSE).

