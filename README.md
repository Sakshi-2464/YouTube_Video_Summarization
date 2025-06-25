A Streamlit web application that summarizes YouTube videos using their transcripts and a transformer-based NLP model (BART). Just paste a YouTube URL and get a concise summary, along with the video’s title and thumbnail.

## Features
- Fetches transcripts from YouTube videos  
- Summarizes content using Hugging Face’s `facebook/bart-large-cnn` model  
- Displays the video’s title and thumbnail  
- Allows summary download as a `.txt` file  

## Technologies Used
- Streamlit  
- YouTube Transcript API  
- yt-dlp  
- Hugging Face Transformers  
- BART (`facebook/bart-large-cnn`)  
- PyTorch  

## Installation
### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/youtube-video-summarizer.git
cd youtube-video-summarizer
```
2. **Install Dependencies**
```bash
pip install -r requirements.txt
```
3. **Run the Application**
```bash
streamlit run final.py
```
## Demo
https://github.com/user-attachments/assets/225f3588-a3d9-49f8-acaf-9ca21ce4b8f1

