# fraud_detection
The Intelligent Auto Insurance Fraud Detection System is a powerful AI-driven application designed to identify potential fraudulent insurance claims. This system provides accurate predictions to help mitigate fraud risks. Users can upload their own claim datasets or rely on a default dataset for fraud detection.
# Features
- AI-Powered Fraud Detection: Utilizes advanced machine learning models to predict the likelihood of fraud in insurance claims.
- Flexible Data Input: Accepts user-uploaded datasets or uses a built-in default dataset.
- Policy Number Lookup: Allows for single claim analysis by entering or selecting a policy number.
- Batch Processing: Processes entire datasets for comprehensive fraud detection.
- Adjustable Threshold: Fine-tune the fraud probability threshold to control sensitivity.
- Interactive Visualization: Presents results in an easily interpretable format with options to download predictions.

# Default Dataset
 If a user does not upload a claim dataset, the application will automatically use a pre-configured default dataset. This default dataset contains a representative sample of insurance claims, ensuring that fraud predictions can still be generated even without user-provided data. The default dataset is useful for:

- Testing and Demonstration: Allows users to explore the functionality and capabilities of the application without needing their own data.
- Benchmarking: Provides a baseline for evaluating the performance of the fraud detection system.
- Backup Analysis: Ensures that fraud detection predictions can be made even if no user data is uploaded.

# How It Works
- Default Dataset Handling: If no file is uploaded, the application uses a default dataset stored in the project directory.
- Processing and Prediction: The default dataset is processed using the same preprocessing pipeline as user-uploaded data, and predictions are made using the trained machine learning model.
- Result Display: Results from the default dataset are displayed in the application interface, and users can view and download these predictions.


# Installation
- Clone the Repository
```sh
git clone https://github.com/expertise03/fraud-detection.git
cd fraud-detection
```
- Install Dependencies
```sh
pip install -r requirements.txt
```

# Usage
1. Run the Streamlit Application
```sh
streamlit run stream_app.py

```
2. Navigate to the Application
- Open your web browser and go to http://localhost:8501
3. Use the Application
- Upload a Claim File: Use the sidebar to upload an Excel file containing insurance claim data.
- Set Fraud Probability Threshold: Adjust the slider to set the threshold for fraud prediction.
- Enter or Select a Policy Number: Enter a policy number manually or select from the dropdown list.
- Submit for Analysis: Click the "Submit" button to process the data and view results.
If no file is uploaded, the system will automatically use the default dataset for analysis.

# Application Interface

- About: Provides information about the application.
- Upload File: Allows users to upload their claim datasets.
- Threshold Slider: Adjusts the sensitivity of fraud detection.
- Policy Number Input: For single claim analysis.
- Results Display: Shows predictions and probabilities for each claim.
- Download Button: Exports the results to a CSV file.

# Background Image

To set a custom background image for the application, place your image file in the specified directory and update the path in the set_background function.

# Model Trained
- The model is trained with XGboost, view it with pkl for PKL file or ipykernel easier view
- The model is trained with Dataset-2-New-1.xlsx
- The test Dataset use default-2-NewNew.xlsx
- Backend Database used as MongoDB Shell.

# Youtube Link Reference: https://www.youtube.com/watch?v=_u2XLT2ASRw

<img width="1918" height="963" alt="Screenshot 2026-01-17 164015" src="https://github.com/user-attachments/assets/dcb84b3b-d972-46ce-959a-054907e90a73" />

<img width="1913" height="1018" alt="Screenshot 2026-01-17 164048" src="https://github.com/user-attachments/assets/52913d54-dfe9-44c6-9a20-dcf075bd67b2" />

<img width="1919" height="969" alt="Screenshot 2026-01-17 164116" src="https://github.com/user-attachments/assets/8c8d3174-0ad9-4186-a444-e2bb5fd0ab9f" />

<img width="1919" height="957" alt="Screenshot 2026-01-17 164147" src="https://github.com/user-attachments/assets/0e937333-8735-478e-9e11-42d18e4e37cc" />

<img width="727" height="839" alt="Screenshot 2026-01-17 164357" src="https://github.com/user-attachments/assets/e602609e-1476-4af5-b6fc-1a9571d4cbfd" />

<img width="1472" height="802" alt="Screenshot 2026-01-17 170240" src="https://github.com/user-attachments/assets/01ee5edd-b280-45e0-acdd-bcab401ab33b" />

<img width="1460" height="942" alt="Screenshot 2026-01-17 170259" src="https://github.com/user-attachments/assets/6f357e18-cda1-4086-bd8b-cafc0093e518" />

<img width="1182" height="767" alt="Screenshot 2026-01-17 170310" src="https://github.com/user-attachments/assets/da526351-cd3f-4bef-9e8d-928f7c7013d5" />











