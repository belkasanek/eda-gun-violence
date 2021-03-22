# [Kaggle Gun Violence Data](https://www.kaggle.com/jameslko/gun-violence-data)
The data is about gun-related incidents in the United States from 2013 till 2018 collected by [non-profit organization](https://www.gunviolencearchive.org/). I reviewed several popular proposals for reducing gun violence and evaluate their potential effect based on the data. Firstly, raising age to buy guns from 18 to 21 would give us about 5.5% reduction. Secondly, ban on automatic weapon would to decrease in another 5%. I examined general, seasonal and week trends of data. I studied difference between holiday and casual days. I investigated tags associated with incidents and amount of killed and injured people in those incidents. I explored most frequent type of weapons and outcomes of their usage. I found out average outcome for shooters and victims depending on their gender. I built histograms for shooters depending on their age for both genders. I performed analysis on geographical distribution of an incidents on state and city level. I ranked states by density of killed people and dangerous of incidents and checked how their ranks changed in time.
### Main findings:
* The number of incidents is increasing by about 3.5 thousand (5%) each year, but the first quarter of 2018 looks promising. The number of incidents decreased by 7%.
* Most frequent type of gun is handguns, but in mass shooting (>=4 dead) part of handguns is decreasing.
![image](https://github.com/belkasanek/kaggle_gun_violence_data/blob/master/images/guns_piechats.png "guns piechats")
* Most shooters age between 18 and 25 then with increasing of age their part is slowly decreasing, but part of young between 15 and 20 also pretty big
![image](https://github.com/belkasanek/kaggle_gun_violence_data/blob/master/images/shooters_age_distribution.png "shooters age distribution")
* Influence of holidays are different. At Thanksgiving and Christmas there are less incidents and at New Year and 4th of July more compared to casual days.
![image](https://github.com/belkasanek/kaggle_gun_violence_data/blob/master/images/holiday_vs_casual.png "holiday vs casual")
holiday_vs_casual
* There is a lot of incidents in south states, but incidents in west states are more dangerous.
![image](https://github.com/belkasanek/kaggle_gun_violence_data/blob/master/images/density_map.png "density map")
![image](https://github.com/belkasanek/kaggle_gun_violence_data/blob/master/images/average_num_killed_map.png "average number of killed")
* Big cities have more incidents, especially in Chicago.
![image](https://github.com/belkasanek/kaggle_gun_violence_data/blob/master/images/cities_changes.png "cities changes")
* It doesn't seem what any particular state has successful strategy for reducing gun violence.

### Interactive maps
Some of the maps made with [plotly](https://plot.ly/). They can be seen properly through [Nbviewer page](http://nbviewer.jupyter.org/github/belkasanek/kaggle_gun_violence_data/blob/master/gun_violence_eda.ipynb).
