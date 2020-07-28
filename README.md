# Project: The Relationship Between People's Music Preferences and Their Health Lifestyle

**Made by Team:**
1. Albert Lilian Thamson (2201754412)
2. **Daniel Santoso (2201756506) (me)**
3. Luwis Lim (2201761771)
4. Steven Odolf Yuwono (2201758045)

**Dataset from:**

- https://www.kaggle.com/miroslavsabo/young-people-survey#responses.csv
- From our own questionnaire

**Description:**

This project is my final project for the Machine Learning course in my Semester 4 of Computer Science Major at BINUS University.

The project is to make a research to determine whether one's music preferences are affects one's health lifestyle, specifically one's smoking habits. This project uses 2 datasets, each with the same columns of many music genres (how much does a person like a music genre from 1-5) and their smoking habits (smoker or not), but the difference is that 1 dataset is filled by all Slovakian nationalities and the other dataset is filled by all Indonesian nationalities. The Slovakian dataset also have more rows than of the Indonesian dataset.

The methods we use to process the data and get insight are:
1. Linear Regression
2. Polynomial Regression
3. Support Vector Machine (SVM)
4. Decision Tree
5. K-th Nearest Neigbour (KNN)
6. Random Forest

To see the full explanation on this research, please kindly open our report on the folder "Report" with the file name of "Laporan Project Machine Learning_AlbertDanielLuwisSteven"

**How to Use:**
1. Open any .ipynb files you want to open to check the code and results of the specific method.
2. Run all the codes on the file.

**Results:**

Form the various methods that we used, the best result that we obtain was using the Random Forest method. Using the Random Forest model, the Slovakian dataset got an accuracy of 66.59%, meanwhile the Indonesian dataset got an accuracy of 93%. For the conclusion, we found out that people's music preferences does not relate or affect their smoking habits. The Slovakian dataset shows very low relations between music preference and smoking habits, but the Indonesian dataset shows a little bit of relation between some music genre preferences and the smoking habit of the person who likes that specific music genre, that is Rock n Roll and Punk.

Here are the results...

Slovakian Dataset using Random Forest:

![](/results/slovak.png)

Indonesian Dataset using Random Forest:

![](/results/indo.png)
