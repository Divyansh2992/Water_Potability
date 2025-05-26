# Water Potability Prediction App

This is a Streamlit web application that predicts whether water is potable (safe to drink) based on various water quality metrics. The app also provides interactive data visualizations and statistical summaries of the dataset.

## Features
- **Water Potability Prediction:** Enter water quality parameters and get a prediction (potable or not potable) using a trained machine learning model.
- **Prediction Probability:** View the probability/confidence of the prediction.
- **Data Visualization:** Explore the dataset with customizable plots (histogram, scatterplot, barplot, boxplot).
- **Statistical Information:** View descriptive statistics for potable and non-potable water samples.
- **Author Profiles:** Links to the author's LinkedIn, GitHub, and Kaggle profiles.

## Files
- `water_potability_app.py` — Main Streamlit app.
- `water_potability_predictor.pkl` — Trained model, scaler, and input columns (used by the app).
- `water_potability_preprocessed.csv` — Preprocessed dataset for visualization.
- `requirements.txt` — List of required Python packages.

## How to Run Locally
1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd <repo-folder>
   ```
2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the app:**
   ```sh
   streamlit run water_potability_app.py
   ```
4. Open the provided local URL in your browser.

## How to Deploy on Streamlit Community Cloud
1. Push your code to a public GitHub repository.
2. Go to [Streamlit Cloud](https://streamlit.io/cloud) and sign in with GitHub.
3. Click "New app", select your repo and branch, and set the main file to `water_potability_app.py`.
4. Click "Deploy". Your app will be live at a public URL.

## Water Quality Parameters Used
- ph
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic_carbon
- Trihalomethanes
- Turbidity


