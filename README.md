# 🎵 SpectroTune AI  

SpectroTune AI is a project that scrapes trending songs from YouTube, generates spectrograms, and analyzes them using a machine learning model.  
<p align="center">
  <img src="https://github.com/user-attachments/assets/e4c253ed-88c7-4419-b6ad-daea8d12192b" width="200">  
  ➡️  
  <img src="https://github.com/user-attachments/assets/5364980e-4666-4dad-8d4a-501cffcc465c" width="200">
</p>
➡️  
Notre Modèle analyse les couches musicales et extrait les tendances actuelles.
## 🚀 Features  
- Scrapes top songs from YouTube using **yt-dlp**  
- Converts audio to spectrogram images using **Librosa & Matplotlib**  
- Feeds spectrograms into a deep learning model for analysis  
- Supports classification, genre prediction, or custom ML tasks  

## 📦 Installation  

Clone the repository:  

git clone https://github.com/your-username/spectrotune-ai.git
cd spectrotune-ai
Install dependencies:

pip install -r requirements.txt

## Usage
**Scrape songs from YouTube:**
python scrape_youtube.py
**Convert audio to spectrograms:**
python generate_spectrograms.py
**Train and run the model:**
python train_model.py
## Project Structure
📂 SpectroTune-AI  
 ├── scrape_youtube.py        # Scrapes trending songs  
 ├── generate_spectrograms.py # Converts audio to spectrograms  
 ├── train_model.py           # Machine learning model  
 ├── data/                    # Audio & spectrogram storage  
 ├── models/                  # Trained models  
 ├── README.md                # Project documentation  
 ├── requirements.txt         # Dependencies  
