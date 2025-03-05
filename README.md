# 🎵 SpectroTune AI  

SpectroTune AI is a project that scrapes trending songs from YouTube, generates spectrograms, and analyzes them using a machine learning model.  

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
