# Machine Learning Model

> **Overview** 
In this practical application, the goal is to compare the performance of the classifiers, namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. The data was collect by Portuguese bank that used its own contact-center to do directed marketing campaigns. The telephone, with a human agent as the interlocutor, was the dominant marketing channel, although sometimes with an auxiliary use of the Internet online banking channel (e.g. by showing information to specific targeted client).

> **Business Understanding**
The business goal is to find a model that can explain success of a contact with client, i.e. if the client subscribes the term deposit. The classification model can increase campaign efficiency by identifying the main characteristics that affect success, helping in a better management of the available resources (e.g. human effort, phone calls, time) and selection of a high quality and affordable set of potential buying customers.

> **Data Understanding**
The dataset comes from the UCI Machine Learning repository [link](https://archive.ics.uci.edu/ml/datasets/bank+marketing). The data is from a Portugese banking institution and is a collection of the results of multiple marketing campaigns. The article accompanying the dataset [here](CRISP-DM-BANK.pdf) is being referred for more information on the data and its features.
> To find the effectiveness of marketting campaigns, Portugese bank reached out to customers from their contact centers and collected the customer perspective. This collected data along with the internal customer data within bank was used to prepare the dataset features for analysis. The classification goal was to determine if a client will subscribe to a term deposite. The team used 3 iterartions of campaign to fine tune the predective model

> **Data Preperation**
The data is first analysed on the missing or NAN elements, then the data aggregration is done to analyse the trend & unique components in column and row wise.The dataset features is being analysed by generating the correlation matrix      

> **Repo Notebook**
The link to repor - 

> **Tech Stack**
>> ***Language*** Python
> > 
> > ***Packages***
Pandas, Numpy
Seaborn, Plotly, Matplotlib, Simple Imputer, Column Transformer, TargetEncoder, LabelEncoder, StandardScaler, Pipeline, OneHotEncode, Ordinal Encoder, PCA, RandomForestClassifier, train_test_split,
DummyClassifier, classification_report, accuracy_score,roc_curve, roc_auc_score, LogisticRegression, KNeighborsClassifier, DecisionTreeClassifier, SVC, mutual_info_regression, GridSearchCV

##### This'll be a _Helpful_ Section About the Greek Letter Θ!
A heading containing characters not allowed in fragments, UTF-8 characters, two consecutive spaces between the first and second words, and formatting.

   




