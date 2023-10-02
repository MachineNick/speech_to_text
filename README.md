# SpeechToText-app

# 1. Obtain the AssemblyAI API key

# 2. Running SpeechToText as command line tool

Firstly, install prerequisite `pytube` library by typing the following:
```
pip3 install pytube
```

Secondly, run the SpeechToText by typing the following (note that you can replace the URL with a YouTube video of your choice):
```
python3 run.py -i "https://www.youtube.com/watch?v=xqyUdNxWazA"
```

# 3. Running SpeechToText as a Streamlit app
Steps to recreate this web app on computer.

### Create conda environment (Optional)
Firstly, we will create a conda environment called *SpeechToText*
```
conda create -n run python=3.7.9
```
Secondly, we will login to the *SpeechToText* environment
```
conda activate SpeechToText
```

###  Pip install libraries
```
pip install -r requirements.txt
```

###  Launch the app

```
streamlit run app.py
```
