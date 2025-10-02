
# 🌽 Maize Crop Yield Prediction

This project predicts **maize crop yield (in tons/hectare)** using machine learning (Random Forest) and a **React frontend** for user interaction.  
The model helps farmers and researchers estimate yield based on environmental and agricultural factors.

---

## 🚀 Features
- **Frontend**: Built with React for a simple and interactive UI.  
- **Backend**: Machine learning model trained using **Random Forest**.  
- **Input Parameters**:
  - `sowingDate`
  - `nitrogenApplied`
  - `phosphorusApplied`
  - `soilPh`
  - `averageTemperature`
  - `averageRainfall`
  - `averageHumidity`
  - `plantDensity`
  - `seedType` (e.g., *Hybrid*)  

- **Output**: Predicted **yield (tons/hectare)** as a single numeric value.  

---

## 📂 Project Structure
```

.
├── project/        # Frontend 
├── README.md       # Project documentation

````

---

## ⚙️ Tech Stack
- **Frontend**: React, JavaScript, CSS  
- **Backend**: Python (Flask / FastAPI)  
- **ML Model**: Random Forest (scikit-learn)  
- **Data Handling**: Pandas, NumPy  

---

## 🖥️ Installation & Usage

### Clone the Repository
```bash
git clone https://github.com/your-username/maize-yield-prediction.git
cd maize-yield-prediction
````

### Backend Setup

```bash
cd backend
pip install -r requirements.txt
python app.py
```

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

Open your browser at **[http://localhost:3000](http://localhost:3000)** 🚀

---

## 📊 Example

### Input:

```json
{
  "sowingDate": "2025-06-01",
  "nitrogenApplied": 120,
  "phosphorusApplied": 60,
  "soilPh": 6.5,
  "averageTemperature": 25,
  "averageRainfall": 120,
  "averageHumidity": 70,
  "plantDensity": 30000,
  "seedType": "Hybrid"
}
```

### Output:

```json
{
  "predictedYield": 6.8  // tons/hectare
}
```

---

## 🌱 Applications

* Helps **farmers** optimize crop management.
* Useful for **agricultural researchers**.
* Can assist in **food security planning**.

---

