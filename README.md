### Name : Shrikant Sahu, Roll No.: 1911113

### Class : SY COMPS B

### Course : RDBMS

### Faculty Name: VPV Sir & PYB Ma'am

### College Name: KJSCE

### Topic: Real Time Fake News Detection using machine Learning and nlp

# 1. Prerequisites: 
Install the required libraries like sk-learn, flask, nltk, wordcloud, numpy, pandas, etc. They are necessary to run the notebook file present in the project. 
You can use pip commands or conda commands to install them. 

# 2. Downloading the Project:
1) Firstly, go to the folder directory where you want to keep the project. 
2) Then use the command:
3) git clone https://github.com/shrikantsahu2004/RDBMS_IA2_Fake_News_Detection.git
4) This will clone the project in your PC.

# 3. Running the Project:
For just running the project, follow these steps:
1. In the app.py file present in the App Folder, inside the joblib.load() function, change the path to the path of the fakenewspipeline.sav file present in your device.
2. Then, run the app.py file.
3. This will run the project in the port mentioned. Press Ctrl+click on the link shown in the terminal/shell to follow the link or copy paste it in your browser.
4. This will render the index.html file where you can enter the news details and then click on the predict button to predict the news type.

# 4. Creating your own Pipeline:
If you want to create your own model, follow these steps:
1. Open the .ipynb file (only one such file present).
2. If you want to use a different dataset, read the dataset accordingly(in the read_csv() function, change the path).
3. Now there is a chance that for your datasets, the model could give different accuracies, hence accordingly change the model and feature extraction technique used in the pipeline function used. 
4. You can give a path where you want to save your pipeline.
5. Now, in the app.py file present in the App Folder, inside the joblib.load() function, change the path to the path of the pipeline file that you just produced.
6. Follow the steps mentioned in Running the Project section.

### In case you need any help, refer these official documentations:
For package installations, refer https://packaging.python.org/tutorials/installing-package/ , https://anaconda.org/anaconda/repo
For information regarding machine learning and nlp libraries and functions, refer https://scikit-learn.org/stable/user_guide.html











