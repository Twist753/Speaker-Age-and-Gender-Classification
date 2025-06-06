# Speaker-Age-and-Gender-Classification
For this Project I used Mozilla Common Voice dataset(Hindi). Each dataset only consist of some useful data as vadidated.csv, thus I used several such validadted.csv and clips folder from various versions and combined them together. The custom dataset can be obtained from the following drive link:

Dataset link - https://drive.google.com/drive/folders/1rRPA5EdV8jiNyVuAcY1-IUCMLGpa7VMu?usp=drive_link

This project contains: 

1) "ReadME" file with custom dataset link and information
2) "main.ipynb" file as main python notebook script

Steps:
1) Download the custom dataset "data" folder from link provided or download direct dataset from Mozilla Common Voice.

2) Now Run "main.ipynb" python notebook. The "main" consist of 3 modules:

Dataset Generator - merge the audio clips location and tsv files(tab separated values) into a single csv file and performs data cleaning. Generates a csv file named     "final_csv_dataset.csv". Need to provide the location of "data" folder.

Model Development - Train and test LSTM based models for both 'age' and 'gender' prediction. Creates 2 models as "age_lstm_model.h5" and "gender_lstm_model.h5"

Real-Time GUI - Provides a user interface using a python library 'gradio' and 'soundfile'. [only works on google colab]
Instructions:
1) Click on the public URL below.
2) Press RECORD on left side, it might ask for mic permissions so provide it.
3) Record an audio of max 5s and press STOP. Then press SUBMIT to submit the audio. The result can be seen on right-side pane.
NOTE - You might need to press SUBMIT a few times to get the result. ;)

Evaluation (validation accuracy):
Gender Model - 0.98
Age Model - 0.95

![image](https://github.com/user-attachments/assets/866d9add-6cfc-491b-9d58-905e55066ec0)   ![image](https://github.com/user-attachments/assets/36e64370-a796-49ae-8ff5-b4aeb5de7400)

Gradio GUI:
![image](https://github.com/user-attachments/assets/44b1b472-c39e-43b7-8451-feb42006d0ca)

