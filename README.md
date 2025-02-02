# Dicoding-Collection-Dashboard-
Cara Run Dashboard

# Setup Environment - Anaconda
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt

# Setup Environment - Shell/Terminal
mkdir Proyek Analisis Data
cd Proyek Analisis Data
pipenv install
pipenv shell
pip install -r requirements.txt

# Run steamlit app
cd Dashboard
streamlit run dashboard.py
