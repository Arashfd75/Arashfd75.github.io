---
title: Projects
# layout: categories
excerpt: "Category index"
aside: true
---
1. Twitter API and Iran Protest Analysis
2. Wildfire Classification on Embedded Systems
3. Image Colorizationalgorithm for recolorization of surveillance images
4. Volleyball Game!
{:toc}
### Iran Protests Analysis
<p style='text-align: justify;'>   
On September 13, 22-year-old Jina “Mahsa” Amini was arrested by Iran's morality police for “improperly” wearing her hijab, and according to her family and local media, severely beaten. She died three days later while still in police custody. In this project, I analysed twitter activity around this matter.
</p>
Some of important notes:

1. I used Twitter API V2. 
2. The main metrics of this study are counts of MahsaAmini and Strikes hashtags in Farsi language. People have been using #MahsaAmini from the first day of the protests which makes this hashtag an ideal metric. 
3. Important incident have been noted on the plot and their impact on the trend of #MahsaAmini is shown.
4. US Dollar rate is shown on the same figure. 
5. The result are illustrated using Power BI.
6. The queries are stored in pandas dataframe and are set to always get information from the first date of the protests until now.

{% include figure.html image="https://github.com/Arashfd75/Arashfd75.github.io/blob/main/assets/images/IranProtests29Dec.jpg?raw=true" caption="Iran Protest infographic" %}
---
### Wildfire classification model for low-power embedded systems
<p style='text-align: justify;'>   
Unmanned Aerial Vehicles (UAVs) have always been faced with power management challenges. Managing power consumption becomes critical, especially in surveillance applications where the longer flight time results in wider coverage and a cheaper solution.
While most current studies focus on utilizing new models for improving event detection without considering the power constraints, our design's first priority is our platform's power efficiency. Implementing an algorithm on a portable device with minimal access to power supply sources requires special hardware and software considerations.
</p>
{% include figure.html image="https://github.com/Arashfd75/Arashfd75.github.io/blob/main/assets/images/overview.jpg?raw=true" caption="Overview of wildfire detection" %}
---
### Image colorization
<p style='text-align: justify;'>   
When the UAV detects the defined event, a sample image is sent to
the server for validation. Afterwards, if the server validates the drone decision, the drone, which can be a
UAV, starts sending a colored image accompanied by a group of N grayscale images. Then, in the server,
the grayscale images will be colorized using a convolution neural network trained by the colored images.
{% include figure.html image="https://github.com/Arashfd75/Arashfd75.github.io/blob/main/assets/images/colorization_pictures.png?raw=true" caption="Image colorization" %}
</p>
---
### Twitter Trends  Dashboard
<p style='text-align: justify;'>
In this project, I designed a user interface based on Django and Dash-Plotly for my twitter application. Users in this web application can insert the hashtag they are looking for in addition to the time interval. Then thier request will be processed and a figure will be plotted. Using the Plotly interactive plots, users are able select different parts of the output figure based on their interest. The user inputs are handled using the callback functions in the application backend. The next step is to deploy this tool which is in process now.
{% include figure.html image="https://github.com/Arashfd75/Arashfd75.github.io/blob/main/assets/images/djangoWeb.png?raw=true" caption="Twitter Trends Plotter Dashboard" %}
 </p>

---
### Volleyball game!
<p style='text-align: justify;'>   
There were 24 people inculding me who wanted play volleyball. As you may know, volleyball is played in teams of 6. So, there was an argue over the number of teams:
 </p>
1. 3 teams of 8 (2 substitue players)
2. 4 teams of 6 (No substitutuions)
<p style='text-align: justify;'> 
At the beginning, mose people were thinking that the first option (3 teams) would be more efficient and they suggested to do the substitutions each 6 points. However, I was of the opinion that I may not be fair for all players, so I decided to do some simulations and visualizations.
{% include figure.html image="https://github.com/Arashfd75/Volleyball_game_poll/blob/main/images/histAll.png?raw=true" caption="Histogram of points played by all players in a game. (first team reach 15 wins)" %}

As the image above shows, there are three different peaks for number of points a player plays in a single game. This starting position of a position affects the total points played by a player. As a result **it would not be fair to play in such manner and it would we better to play in 4 teams of 6.**
 </p>
---
### Leaf Nitrogen Classification
<p style='text-align: justify;'>   
The nitrogen level is a critical parameter that makes the plant performs well. Therefore, this amount should be monitored in order to devise a plan for soil fertilization. In this project, the amount of nitrogen will be classified into the n groups by using different classification methods utilizing a spectrophotometer. The n depends on the dataset which is in this case 4. In our dataset, each group of plants is fertilized with a certain amount of nitrogen to make different groups. There are groups of samples with 0, 6, 12, and 20 grams concentrations of nitrogen. The number of samples is 2478 before adopting the K-means clustering method (K=3) which reduces the number of samples to one-third. After adopting the feature selection method and normalization, different classification methods will be used to build a model in which the plant’s nitrogen class is identified. In this study, three classification methods of k-nearest neighbors (KNN), decision tree, and support vector machines (SVM) are used in which the best results were achieved by SVM with 88.88% accuracy followed by KNN with 86.98% of accuracy. The normalization stage significantly increases the performance of the two mentioned classifiers while having a minimal positive effect on the decision tree classifier. Besides, setting proper hyper-parameters for the classifiers can notably rise the performance.
 </p>
{% include figure.html image="https://github.com/Arashfd75/Arashfd75.github.io/blob/main/assets/images/leaf_nitrogen.jpg?raw=true" caption="Leaf Nitrogen Classification" %}
---


