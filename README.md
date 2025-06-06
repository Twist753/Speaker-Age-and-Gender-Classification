# Speaker-Age-and-Gender-Classification

This project contains: 

1) "data" folder with all the audio clips and dataset structure
2) "main.ipynb" file as main python notebook script

The "main" consist of 3 sections:

1) Dataset Generator - merge the audio clips location and tsv files(tab separated values) into a single csv file and performs data cleaning. Generates a csv file named "final_csv_dataset.csv"

2) Model Development - Train and test LSTM based models for both 'age' and 'gender' prediction. Creates 2 models as "age_lstm_model.h5" and "gender_lstm_model.h5"

3) Real-Time GUI - Provides a user interface using a python library 'gradio' and 'soundfile'. [only works on google colab]
Instructions:
1) Click on the public URL below.
2) Press RECORD on left side, it might ask for mic permissions so provide it.
3) Record an audio of max 5s and press STOP. Then press SUBMIT to submit the audio. The result can be seen on right-side pane.
NOTE - You might need to press SUBMIT a few times to get the result. ;)


If you are running the code locally (i.e. on vscode or jupyter), run the last few commented cells.
