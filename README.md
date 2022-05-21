# realtime-transcription

# Watch the tutorial video

[How to Build a Real-Time Transcription Web App in Python using AssemblyAI and Streamlit](https://youtu.be/Kj0JtjAxxKA)

<a href="https://youtu.be/8rb9GefC_CU"><img src="http://img.youtube.com/vi/8rb9GefC_CU/0.jpg" alt="How to Build a Real-Time Transcription Web App in Python using AssemblyAI and Streamlit" title="How to Build a Real-Time Transcription Web App in Python using AssemblyAI and Streamlit" width="500" /></a>

# 1. Obtain the AssemblyAI API key

Obtain your free [AssemblyAI API key](https://www.assemblyai.com/?utm_source=youtube&utm_medium=social&utm_campaign=dataprofessor_realtime).

# 2. Running the real-time transcription web app
To recreate this web app on your own computer, do the following.

### Create conda environment (Optional)
Firstly, we will create a conda environment called *transcription*
```bash
conda create -n transcription python=3.9
```
Secondly, we will login to the *transcription* environment
```bash
conda activate transcription
```

###  Download GitHub repo

```bash
git clone https://github.com/dataprofessor/realtime-transcription
```

###  Pip install libraries
```bash
pip install -r requirements.txt
```

###  Launch the app

```bash
streamlit run streamlit_app.py
```
