# ADS-Studio
ADS-Studio is a Machine Learning Application designed to help you automate the machine learning process and also save time.ADS-Studio enables individuals to draw meaning out of their dataset within  shortest possible period without going through any complex processes.It enables users to quickly perform exploratory data analysis, data visualization, data cleaning, preprocessing and building of machine learning models.

### Product Perspective
ADS-studio is a web application and it can be accessed using a web browser like Microsoft Edge, Google Chrome, and the like.

### Product Function
The ADS-Studio enables a user to perform the following functions with just a click:
* Enable a user load his or her own dataset(CSV, txt, json, xls)
* Perform Exploratory Data Analysis( EDA)
* PErform Data cleaning 
* Perform Data visualization(Pie Chart, correlation Matrix, pairplot, scatter and more)
* Preprocess the dataset for model building
* Build Preferred Model(Regression, Classification, Clustering)
* Use the model for inferencing

### Who can use ADS-Studio?
* Experts in the data science field who wishes to automate the data science process and save time for other equally important projects.
* Non-data science experts who seeks to draw meaning out of their dataset.

### Dependencies
* Python
* Streamlit 


### Work Flow in ADS-Studio
This section describes how an individual will be able to use the ADS-Studio to work on his or her dataset.The flow begins when the user navigates to the Home page. The user can browse through the available list of functions in the ADS- studio at the upper-left side of the studio and then selects one of the following functions:
*    EDA
*    Data Cleaning
*    Visualization
*    Machine Learning

![4ewjfq](https://user-images.githubusercontent.com/68768460/93087222-ca1ae700-f687-11ea-81a7-7e751c2f30c9.gif)

When the user decides to select EDA, the studio will allow the user to input his or her preferred dataset(csv, xls, txt, json) and then will be presented with the options below:

*    show shape (to visualize the number of rows and columns in dataset)
*    show columns( to view the names of the columns)
*    show summary( to view basic statistics of the dataset)
*    value counts 
*    show null values

when the user selects any of the options above, the result is automatically generated. More EDA options will be added in a short while.

![2](https://user-images.githubusercontent.com/68768460/93088719-d011c780-f689-11ea-8754-f4f7ff5865b8.gif)

\
\
Likewise when the user selects visualization , he or she will be allowed to visuallize a number of graphs based on the option he or she chooses. Some of the graphs the user can visualize are as follows:

*    pie chart
*    correlation matrix
*    Histogram
*    Pairplot
*    Scatter Plot
*    Bar graph

When the user selects the preferred option above, the graph is automatically generated for the user without any complex process.

However, a user can decide to go to the visualization section directly without going through the EDA section. Also, a dataset uploaded by a user at the EDA section remains in memory and can be used by the user in other section without necessarily reloading.

![3](https://user-images.githubusercontent.com/68768460/93089615-11ef3d80-f68b-11ea-8842-e72d89c9456d.gif)


In a similar way, the user can decide to select the data cleaning section  where the user will be able to tidy his or her dataset with just a click.

When the User selects Machine Learning, ADS-Studio will automatically clean the dataset by removing all null rows and then performs label encoding on all the categorical columns. It then asks the user to select the target column and also the feature columns.The user has the option to enter the test size and the random state.

![4](https://user-images.githubusercontent.com/68768460/93090789-cc337480-f68c-11ea-8272-ef5c35a3e136.gif)

It then presents the user with the option to select the type of model he or she wishes to build based on the dataset. That is the following models:
*    Regression
*    Classification
*    Clustering

When the user selects Regression, the ADS-Studio automatically generates the regression results. The User is then asked to select a number of visualizations based on the metrics generated.(The current Regression model is a Linear Model. Other types of Regression models will be added in short while).The User can then visualize the Regression metrics by selecting Visualize Metric results. Also the user can then input a new dataset without the target column to make inference.

![4ewqhv](https://user-images.githubusercontent.com/68768460/93092268-bf178500-f68e-11ea-9cad-546716c6b31a.gif)


 However, when the user selects Classification the user is presented with the following models to select from:
 *    SVC
 *    Decision Tree
 *    Random Forest
 *    KNN
 *    Naive Bayes
 
 When the user selects aany of the above models, ADS-Studio automatically generates classification results.
 
   ![6](https://user-images.githubusercontent.com/68768460/93094928-09e6cc00-f692-11ea-831b-1870c1493c2d.gif)
    
  The user can then decide to view the follwing metrics with their corresponding results and also make predictions with a dataset without a target column:
  *    Confusion Matrix
  *    ROC- Curve
  *    Precision -Recall Curve.
  *    Make predictions 

![7](https://user-images.githubusercontent.com/68768460/93096341-c8efb700-f693-11ea-883a-fa893d62629d.gif)

### Way Forward 
We seek to add more features in the future and also to make the interface more user friendly.

### Acknowledgement 
Azubi Africa\
Microsoft4Afrika\
Samuel Manu\
Richmond Chris-Koka\
Sharon Bosire

### Collaborators
Emmanuel Akpe(emmanuelakpe1@gmail.com)\
Emmanuel Osabutey(emmanuel.osabutey@azubiafrica.org)\
Alfred Ametepey(alfred.ametepey@azubiafrica.org)







