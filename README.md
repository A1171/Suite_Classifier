In this example project I parsed websites and trained classifier.

site_types_2_demo.txt  - dataset example. datafile with website links, separated by category name

Site Classifier_demo.ipynb - Parsing data + training classifier


To use this notebook, fill site_types_2_demo.txt wit your website categories and links. It is recomended to use at least 50 links for each category. Create Project folder on Google drive. Place site_types_2_demo.txt file in created Project folder on Google drive. Put path to Google drive folder in "ProjectFolder" variable "Headers" section of Colab notebook. Example: ProjectFolder="/content/drive/MyDrive/NN/SuiteClassifier1/". Put list of categories in variable of "Headers" section of Colab notebook. Example: "Captions=["CrashComisar","WaterWell","electric","evacuator","PCHelp","DoorBreak","Doors","GlassRepair"]". Now you can start Colab notebook.

LSI model show better results with high category amount. Good choice for selection amount of topics of LSI num_topics=Amount of categories * 5
