# GSC-2025
Google Solution Challenge 2025

# AI-Based Electricity Demand Projection for Delhi Power System

## Project Overview
This project is part of **Smart India Hackathon 2024**, focusing on developing an **AI-based model for electricity demand projection**, including peak demand forecasting for the Delhi Power System.

## Execution Steps

### 1. Clone the Repository
```sh
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### 2. Install Dependencies
Ensure you have Python installed, then install the required dependencies.
```sh
pip install -r requirements.txt
```

### 3. Prepare the Dataset
- Download the historical electricity demand dataset from **[Delhi SLDC](https://www.delhisldc.org/)**.
- Place the dataset in the `data/` directory.
- Run preprocessing:
  ```sh
  python preprocess.py
  ```

### 4. Train the Model
Execute the training script:
```sh
python train.py
```

### 5. Evaluate the Model
Run the evaluation script to test the model:
```sh
python evaluate.py
```

### 6. Deploy the Model
- Use **AWS, Azure, or Google Cloud** for deployment.
- Run:
  ```sh
  python deploy.py
  ```

### 7. Run the Web Dashboard
Start the dashboard for visualization:
```sh
streamlit run dashboard.py
```

## Technologies Used
- **Python**
- **TensorFlow/PyTorch**
- **LSTM Networks**
- **Flask/FastAPI**
- **Streamlit** (for visualization)
- **AWS/Azure** (for deployment)

## Contributing
Feel free to contribute by submitting issues or pull requests.

## License
This project is licensed under the **MIT License**.

---

Replace `your-username/your-repository` with your actual GitHub repo URL.

