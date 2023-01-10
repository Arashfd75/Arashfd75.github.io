---
title: Projects
# layout: categories
excerpt: "Category index"
aside: true
---
# Contents

1. [Twitter API and Iran Protest Analysis](Arashfd75.github.io/projects###Iran Protests Analysis)
2. [Wildfire Classification on Embedded Systems](Arashfd75.github.io/projects###Developing a wildfire classification deep learning algorithm for an extra low-power microcontroller for drone application)
3. [Image Colorization](Arashfd75.github.io/projects###Image colorization deep learning algorithm for recolorization of surveillance images)

### Iran Protests Analysis : 
On September 13, 22-year-old Jina “Mahsa” Amini was arrested by Iran's morality police for “improperly” wearing her hijab, and according to her family and local media, severely beaten. She died three days later while still in police custody. In this project, I analysed twitter activity around this matter.

Some of important notes:

1. I used Twitter API V2. 
2. The main metrics of this study are counts of MahsaAmini and Strikes hashtags in Farsi language. People have been using #MahsaAmini from the first day of the protests which makes this hashtag an ideal metric. 
3. Important incident have been noted on the plot and their impact on the trend of #MahsaAmini is shown.
4. US Dollar rate is shown on the same figure. 
5. The result are illustrated using Power BI.
6. The queries are stored in pandas dataframe and are set to always get information from the first date of the protests until now.
{% include figure.html image="https://github.com/Arashfd75/Arashfd75.github.io/blob/main/assets/images/IranProtests29Dec.jpg?raw=true" caption="Iran Protest infographic" %}


### Developing a wildfire classification deep learning algorithm for an extra low-power microcontroller for drone application
Unmanned Aerial Vehicles (UAVs) have always been faced with power management challenges. Managing power consumption becomes critical, especially in surveillance applications where the longer flight time results in wider coverage and a cheaper solution.
While most current studies focus on utilizing new models for improving event detection without considering the power constraints, our design's first priority is our platform's power efficiency. Implementing an algorithm on a portable device with minimal access to power supply sources requires special hardware and software considerations.
{% include figure.html image="https://github.com/Arashfd75/Arashfd75.github.io/blob/main/assets/images/overview.jpg?raw=true" caption="Overview of wildfire detection" %}

### Image colorization deep learning algorithm for recolorization of surveillance images
When the UAV detects the defined event, a sample image is sent to
the server for validation. Afterwards, if the server validates the drone decision, the drone, which can be a
UAV, starts sending a colored image accompanied by a group of N grayscale images. Then, in the server,
the grayscale images will be colorized using a convolution neural network trained by the colored images.
{% include figure.html image="https://github.com/Arashfd75/Arashfd75.github.io/blob/main/assets/images/colorization_pictures.png?raw=true" caption="Image colorization" %}

### Volleyball game!
#### What is this project about?
There were 24 people inculding me who wanted play volleyball. As you may know, volleyball is played in teams of 6. So, there was an argue over the number of teams:
1. 3 teams of 8 (2 substitue players)
2. 4 teams of 6 (No substitutuions)

At the beginning, mose people were thinking that the first option (3 teams) would be more efficient and they suggested to do the substitutions each 6 points. However, I was of the opinion that I may not be fair for all players, so I decided to do some simulations and visualizations.
{% include figure.html image="https://github.com/Arashfd75/Volleyball_game_poll/blob/main/images/histAll.png?raw=true" caption="Histogram of points played by all players in a game. (first team reach 15 wins)" %}

As the image above shows, there are three different peaks for number of points a player plays in a single game. This starting position of a position affects the total points played by a player. As a result **it would not be fair to play in such manner and it would we better to play in 4 teams of 6.**

