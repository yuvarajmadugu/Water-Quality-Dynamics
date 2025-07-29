# 🌊 Predictive Modeling of Long-Term Water Quality Dynamics
A mini project developed as part of the B.Tech (AI & ML) curriculum at Kommuri Pratap Reddy Institute of Technology. This project applies AI and data analytics techniques to model and forecast groundwater contamination and surface water quality trends using spatial, temporal, and environmental data.

### 📘 Project Summary
- This project introduces an AI-driven predictive model that integrates:
- Weighted regression techniques
- Geospatial features (latitude, longitude, elevation)
- Environmental parameters (pH, turbidity, DO, COD, etc.)
- Temporal & seasonal data (discharge rates, monsoon cycles)
The goal is to provide accurate, location-aware forecasts of water quality, aiding sustainable water resource management and early contamination warning systems.

### 🎯 Objectives
- Develop an AI model that can predict water quality over time
- Incorporate spatial and environmental variables
- Use entropy-based feature selection and Pearson correlation
- Enable contamination risk mapping and real-time dashboards

### 🔍 Key Features
| Feature                         | Description                                                                 |
|---------------------------------|-----------------------------------------------------------------------------|
| 🔬 Hybrid AI Modeling           | Combines regression, KNN, and Random Forest models                          |
| 🌐 Geospatial Intelligence      | Considers static features like latitude, longitude, & elevation             |
| 📊 Real-time Visualization      | Dashboard support for live water quality insights and alerts                |
| 🧠 Smart Feature Selection      | Uses entropy and correlation to reduce dimensionality                       |
| 🧪 Accurate Forecasts           | Predicts pH, turbidity, DO, COD, chlorides, alkalinity, and more            |


### 📈 Methodology
- 📥 Data Collection
    pH, turbidity, DO, hardness, COD, temperature, etc.
    Location data: Latitude, longitude, elevation
    Seasonal & discharge volumes
  
- ⚙️ Preprocessing
    Missing value imputation
    Normalization and scaling
    Feature encoding
  
- 🧠 Model Training
    KNN Regressor
    Random Forest Regressor
    Weighted regression using entropy + Pearson correlation
  
- 📊 Evaluation Metrics
    R² (coefficient of determination)
    RMSE 
    MAE

### 🖥️ Software Stack
- Component	Version
- Python	3.7.6
- Pandas	0.25.3
- NumPy	1.19.2
- Scikit-learn	0.22.2.post1
- Matplotlib	3.1.1
- Seaborn	0.10.1
- Jupyter Notebook	

### 🧰 Hardware Requirements
- ✅ Min 4GB RAM (8GB recommended)
- ✅ 1GHz dual-core processor or higher
- ✅ OS: Windows 7+, Linux, or macOS 10.9+

### 📊 Results
- Achieved high predictive accuracy for pH, turbidity, and DO
- Heatmaps showed strong correlations between COD, turbidity, and chlorides
- Successfully demonstrated real-time risk mapping capabilities

### 🌍 Applications
- ✅ Groundwater contamination monitoring
- ✅ Smart cities water management
- ✅ IoT + AI-based water monitoring systems
- ✅ Government policy support
- ✅ Agricultural irrigation planning
- ✅ Public health and early warning systems

### 📌 Future Enhancements
- Integrate IoT sensor data in real time
- Deploy via Flask or FastAPI with a web dashboard
- Expand model to classify contamination levels
- Include satellite or remote sensing data

### 👥 Contributors
- Randhi Ram Kiran (22RA1A6659)
- Yuvaraj Madugu (22RA1A6697)
- Maddati Rakesh (22RA1A6658)

### 📜 License
- This project is part of academic coursework. Use for educational and non-commercial purposes only.

