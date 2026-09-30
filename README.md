## 🔄 Analysis Workflow

```mermaid
flowchart TD

A["Data Acquisition<br/>MF4 / Measurement Data"]
B["Data Loading<br/>Pandas / Excel"]
C["Data Processing & Cleaning<br/>Pandas / NumPy"]
D["User Defined Filtering<br/>Pandas / Streamlit"]
E["Interactive Visualization<br/>Plotly"]
F["Scatter Matrix Analysis<br/>Plotly"]
G["Data Point Selection<br/>Plotly / Streamlit"]
H["Response Surface Modeling<br/>Polynomial RSM / Scikit-learn"]
I["Gaussian Process Regression<br/>GaussianProcessRegressor / RBF Kernel"]
J["Model Validation<br/>R² / RMSE"]
K["VVT Optimization<br/>Python / Scikit-learn"]
L["Final VVT Map<br/>Pandas / Plotly"]

A --> B
B --> C
C --> D
D --> E
E --> F
F --> G
G --> H
H --> I
I --> J
J --> K
K --> L
```

## 🛠️ Analysis Modules

| Module | Tools / Methods |
|---|---|
| Data Acquisition | MF4 / Measurement Data |
| Data Loading | Pandas / Excel |
| Data Processing & Cleaning | Pandas / NumPy |
| User Defined Filtering | Pandas / Streamlit |
| Interactive Visualization | Plotly |
| Scatter Matrix Analysis | Plotly |
| Data Point Selection | Plotly / Streamlit |
| Response Surface Modeling | Polynomial RSM / Scikit-learn |
| Gaussian Process Regression | GaussianProcessRegressor / RBF Kernel |
| Model Validation | R² / RMSE |
| VVT Optimization | Python / Scikit-learn |
| Final VVT Map | Pandas / Plotly |

