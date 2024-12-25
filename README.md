# Face Mask Detection

This project involves detecting whether a person is wearing a face mask using image data. It includes dataset preparation, analysis, and the groundwork for developing a machine learning or deep learning model.

## Project Overview
The notebook demonstrates:
- Loading and organizing the dataset of images with and without masks.
- Performing exploratory data analysis (EDA) to understand class distribution.
- Preparing the dataset for training, validation, and testing.

## Features
- **Dataset Management**: Organizes images into two categories: "with mask" and "without mask."
- **Exploratory Data Analysis**: Counts and analyzes images to ensure balanced datasets.
- **Foundation for Model Training**: Sets up the data pipeline for model development.

## File Structure
```
root
├── dataset/                   # Directory to store the dataset (to be added by user)
│   ├── with_mask/             # Images of people wearing masks
│   └── without_mask/          # Images of people without masks
├── face-mask-detection.ipynb  # Main Jupyter Notebook
├── requirements.txt           # List of dependencies
└── README.md                  # Project documentation
```

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Add the dataset to the `dataset/` directory. Ensure the structure matches the one mentioned above.
2. Open `face-mask-detection.ipynb` in Jupyter Notebook or any compatible environment.
3. Execute the cells to:
   - Load and analyze the dataset.
   - Visualize class distribution.
   - Prepare the data for training.

## Future Enhancements
- Develop a deep learning model (e.g., CNN) for mask detection.
- Implement real-time mask detection using a webcam.
- Optimize the model for deployment on edge devices.

## Dependencies
- Python 3.x
- NumPy
- Matplotlib
- OpenCV
- Pillow
- scikit-learn
