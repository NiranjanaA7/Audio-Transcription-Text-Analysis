# Audio-Transcription-Text-Analysis
Developed a Python project that converts audio into text using AssemblyAI. Performed sentiment analysis, word frequency visualization, and chapter summarization. Built interactive plots and tools inside Jupyter Lab for data exploration.
Great! Since you've uploaded **requirements.txt**, **pkl**, **json**, **txt**, and your **.ipynb** notebook, your project folder is now complete for GitHub.

The notebook includes sentiment analysis, word frequency charts, a word cloud, and automatic chapter summaries.

## **Features**

* 🎧 **Speech-to-Text** transcription using AssemblyAI
* 📊 **Sentiment analysis** (Positive / Neutral / Negative)
* ☁️ **Word Cloud** of top words
* 📈 **Word frequency bar chart**
* 📝 **Transcript download**
* ⏱️ **Clickable chapter summary with audio jumping**
* 📁 Uses `.json`, `.txt`, and `.pkl` saved outputs

## **Project Structure**

```
├── requirements.txt
├── transcript.json
├── transcript.txt
├── speech_data.pkl
├── audio.mp3 
└── notebook.ipynb
```

## **How It Works**

1. Upload an audio file
2. Send it to AssemblyAI for transcription
3. Poll the API until transcription completes
4. Save results as JSON, TXT, and PKL
5. Visualize:

   * Sentiment bar chart
   * Word cloud (Top 100 words)
   * Most frequent words
   * Auto-generated chapter summaries

## **Technologies Used**

* Python
* AssemblyAI API
* Plotly
* WordCloud
* Panel
* hvPlot
* Jupyter Lab

## **How to Run**

1. Install packages:

```
pip install -r requirements.txt
```

2. Add your **API key** into `lib/API_KEY.py`
3. Run the notebook cells in order

<img width="857" height="777" alt="image" src="https://github.com/user-attachments/assets/4fbb302f-ba3b-46dd-99d7-305b1ba6dedd" />

