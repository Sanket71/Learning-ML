Based on data ,
we make parts of ml algorithm, so it became easy for us to predict which algo we should use for high perfomance.

1. **Supervised Learning** :
   if we have inputs(features) and outputs(results) for each datapoint then we can supervised learning algorithms.

   Now in this also data can be of 2 types

   1. Numerical data(means output is numeric like age,weight,cgpa)
   2. Categorical data(like gender,Nation)

   so for Numerical data we use regression supervised Learning and categorical we use Classification Supervised learning model.

   1.1 **Regression**
   so we can make relationship betwen input and output and when new data come we try to predict output using this relationship(equation).
   like age,cgpi,degree and placement(in lakhs) then input is age,cgpi,degree and output is placement.

   1.2**classification**
   Based on some input we have to predict output belongs to which part.
   Example : given skintone,height,weight , predict person belongs to which continent. (just eg required much more features)

2. **Unsupervised Learning**

Exactly oppposite of SUpervised means for some data we are not given output , we have to just clustering this or other.\
![pic of usl](./usl.png)\

There are 4 types of Unsupervised Learning.\
1.1 Clustering \
1.2 Dimensionality Reduction \
1.3 Anamoly Detection\
1.4 Assosiation Rule Learning\

1.1 **Clustering**\
is the process of organizing data point into groups or clusters based on their similarities.
example clustering can group customers with similar purchasing behaviors or categorize news articles by topic without prior labels.

1.2 **Dimensionality Reduction**:\
Sometimes what happen data is so large that processing and training time of model become high,but if we see data carefully, someof the feature are correlated. like if features are [room area, bathroom area] , we have to predict what is price of house ,but here if we observe that room area and bathroom area are corelated like if we add both of this attribute then we get total area of house so we have only one attribute to process rather than 2.

so we can say : simplify datasets by reducing the number of variables (features) while retaining essential information.

it is helpful in visualize and analize the data.because sometimes it is very tough to visualize multi dimensional data ,by reducing it's dimension we easily visulize it.

1.3 **Anamoly Detection:**\
identify data points that deviate significantly from the norm, which may indicate errors, fraud, or novel insights.

![ad1](./ad1.png)\
![ad2](./ad2.png)

1.4 **Assosiation Rule Learning**\
To discover interesting relationships or patterns between variables in large datasets.
There is one famous wallmart research that when they check bill of customers and analyze that when customer buys diapers customer also buy liquor bottle, so it's sale increase darstically. so this way this model helps.\

![arl](./arl.png)

3.**Semisupervised Learning**:\
in this some data is labeled(means for some input , output is available) while for some it is not.
This type of learning helpful when we have to manually we have to assign label for some data, at that point this type of learning help us.
example : in google photos ,firsly for 1 photo it will ask us to give name for that photo, now in any other photo same person or input available then it will give name by itself, evrytime it will not ask for that.

4.**Reinforcement Learning**:\
is a learning method that interacts with the environmnent by producing actions and discovering errors.
example:\
![rl](./rl.jpeg)
