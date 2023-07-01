In this example project I parsed suites and train classifier.

suite_types_2_demo.txt  - dataset example. datafile with suite links, separated by category

Suite Classifier_demo.ipynb - Parsing data + training classifier


To use this notebook, fill suite_types_2_demo.txt wit your suite categories and links. It is recomended to use at least 50 links for each category. Create Project folder on Google drive. Place suite_types_2_demo.txt file in created Project folder on Google drive. Put path to Google drive folder in "ProjectFolder" variable "Headers" section of Colab notebook. ProjectFolder="/content/drive/MyDrive/NN/SuiteClassifier1/". Put list of categories in "Headers" section of Colab notebook. Example: "Captions=["CrashComisar","WaterWell","electric","evacuator","PCHelp","DoorBreak","Doors","GlassRepair"]". Now you can start Colab notebook.

LSI model show better results with high category amount. Good choice for amount of topics selection num_topics=Amount of categories * 5
