**Min-Max normalization** converts values into a specified range.

&#x20;   Xnew = X - Xmin / Xmax - Xmin --> min-max-formula



&#x20;   df\_scaled = scaler.fit\_transform(df) ->short-hand





\--------------------------------------------------->>>

EDA means looking at and understanding your dataset before doing further analysis or machine learning.

&#x20;

&#x20;   EDA = Exploratory Data Analysis

&#x20;   Spread → How far the values are from each other.

&#x20;   Outlier : An outlier is a value that is unusually far from the rest of the data.

&#x20;   Histogram → "How are my values distributed/Frequency?"

&#x20;   Box plot  → "How spread out are my values, and are there unusual values?"

&#x20;   bins -> divides the range into a specified number of smaller intervals (bins).



\------------------------------------------------------------->>>



### **Practical 5: Compute and visualize the correlation matrix :**

&#x20;

&#x20;   **A heatmap** is a way of representing numerical values using different shades/colors.

&#x20;   **Correlation** tells us how two numerical variables are related to each other.

&#x20;

&#x20;   **df.corr()** means correlation:

&#x20;       It looks at the numerical columns in your DataFrame and calculates the correlation between every pair of columns.

&#x20;

&#x20;   **annot** means annotation, basically writing the value inside each box.

&#x20;   **Seaborn** is a Python library used for statistical data visualization.





# Practical 7: Polynomial and Interaction Features :

* Polynomial features create powers of features, while interaction features capture combinations between features.
* poly.get\_feature\_names\_out(df.columns)-> takes the column names from df and uses them to create meaningful names for the new polynomial/interaction features.
* 

























&#x20;

