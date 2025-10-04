 Wearable Sensor-based Stress Detection

## Description
This project aims to detect the stress level of users using data from wearable sensors. The sensors used include:
- Heart Rate
- Steps
- Skin Temperature

The prediction model uses a **Random Forest Classifier** for stress level classification. Data visualization shows trends of heart rate and user activity in relation to stress.

## Dataset
Dataset used: [WESAD Dataset](https://archive.ics.uci.edu/ml/datasets/WESAD) – a public dataset for wearable sensor-based stress detection.

## How to Run
### 1. Clone this repository:
```bash
git clone https://github.com/username/wearable-stress-detection.git
cd wearable-stress-detection
```

### 2. Install dependencies:
```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook:
```bash
jupyter notebook wearable_stress_detection.ipynb
```

### 4. The notebook will demonstrate:
- Preprocessing of wearable sensor data
- Training the Random Forest model
- Evaluating accuracy & confusion matrix
- Visualizing heart rate and stress level trends

## Results
- Random Forest model achieving ~80–90% accuracy
- Visualizations of sensor signals vs stress levels


## Project Structure

```bash
.
├── wearable_stress_detection.ipynb
├── data/
│   └── wearable_data.csv
├── requirements.txt
└── README.md
```

## 🧑‍💻 Author    

M. Afdhal Arief Malik
Aspiring AI Researcher | Backend Developer 

