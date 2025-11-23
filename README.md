# Ran-Forest-Project
RN for tabular and image data set

# Experiments
This project explores Random Forests on two datasets:
1. Heart Disease UCI – Tabular data  
2. Intel Image Classification – Image data  

# Heart Disease UCI
- Accuracy: 0.85  
- Model: RandomForestClassifier(n_estimators=100)

# Intel Image Classification
- Accuracy: 0.91  
- Model: RandomForestClassifier on flattened image pixels

Dataset	Source (Kaggle link)	
Heart Disease UCI	https://www.kaggle.com/datasets/ronitf/heart-disease-uci
	Tabular
Intel Image Classification	https://www.kaggle.com/datasets/puneet6060/intel-image-classification
	Image
# RandomForest ML Project

# GitHub Repository
https://github.com/sadiarehman107023/RandomForest-MLProject



## How to Reproduce Experiments
Follow these steps in **Command Prompt** or **PowerShell**:

# 2️⃣ Create and activate a conda environment
conda create -n rf_mlproj python=3.11 -y
conda activate rf_mlproj

# 3️⃣ Install all required Python packages
pip install -r requirements.txt

# 4️⃣ Run the main experiment script
python model_comparison.py

1. **Clone the repository**  
   Open Command Prompt or PowerShell and run:
   ```bash
   git clone https://github.com/sadiarehman107023/RandomForest-MLProject.git
   cd RandomForest-MLProject
