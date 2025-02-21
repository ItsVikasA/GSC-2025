# GSC-2025
Google Solution Challenge 2025

# AI-Based Electricity Demand Projection for Delhi Power System

## Project Overview
This project is part of **Google Solution Challenge 2025**, focusing on developing an **AI-based model for electricity demand projection**, including peak demand forecasting for the Delhi Power System.

## Execution Steps

### 1. Clone the Repository
```sh
git clone https://github.com/ItsVikasA/GSC-2025.git
cd GSC-2025
```

### 2. Install Dependencies
Ensure you have Python installed, then install the required dependencies.
```sh
pip install -r requirements.txt
```

### 3. Prepare the Dataset
- The project includes two CSV files containing historical electricity demand data.
- Place these files in the `data/` directory.

### 4. Train the Model
Open **VS Code**, redirect to **Jupyter Notebook**, and execute the training script:
```sh
jupyter notebook
```
- Open `train.ipynb` and run all cells.

### 5. Evaluate the Model
Run the evaluation script in Jupyter Notebook:
```sh
jupyter notebook
```
- Open `evaluate.ipynb` and run all cells.

## Technologies Used
- **Python**
- **TensorFlow/PyTorch**
- **LSTM Networks**
- **Flask/FastAPI**
- **Streamlit** (for visualization)

## Dataset Information
The dataset consists of:
- **CSV File 1**: Contains historical electricity demand data spanning multiple years with timestamps.
- **CSV File 2**: Includes electricity demand data for a specified month, along with additional features such as weather conditions, holidays, and other external factors affecting electricity demand.

## Contributing
Feel free to contribute by submitting issues or pull requests.

## License
This project is licensed under the **MIT License**.

---
