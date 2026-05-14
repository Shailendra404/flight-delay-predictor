# ✈️ Flight Delay Predictor

A machine learning project that predicts whether a US domestic flight will be delayed by more than 15 minutes.

## 📊 Dataset
- 2015 US Flight Delays (Kaggle / US DOT)
- 5.8 million flight records
- 100,000 rows used for training

## 🤖 Model
- 15 models compared automatically
- **XGBoost selected** — Accuracy: 82.4%, AUC: 0.707

## 🌐 Web Application
- Flask backend REST API
- HTML/CSS/JS frontend
- Deployed via Cloudflare Tunnel from Google Colab

## 📁 Files
| File | Description |
|------|-------------|
| `Flight tracker.ipynb` | Main Colab notebook — data loading, training, evaluation |
| `flight_predictor.html` | Web app frontend — open in browser |
| `flight_delay_model.pkl` | Saved trained XGBoost model |

## 🚀 How to Run
1. Open `Flight tracker.ipynb` in Google Colab
2. Mount Google Drive and run all cells
3. Copy the Cloudflare tunnel URL
4. Open `flight_predictor.html` in browser
5. Paste the URL and start predicting!

## 👨‍💻 Made by
Shailendra kumar singh— Chandigarh University, 2026
