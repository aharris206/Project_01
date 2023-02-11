# Project-01 - Drought and its Effect on Wildfires throughout California
   •   `2023-02-07T21:36−08:00`
## Aster Harris, Lauren Huffmire, Maddy Gutieruiz, Sara Zhu, Terry Goins

# Project Background

Climate change, primarily caused by the burning of fossil fuels, is increasing the frequency and severity of wildfires not only in California but also all over the world. Since 1950, the area burned by California wildfires each year has been increasing, as spring and summer temperatures have warmed and spring snowmelt has occurred earlier.- California Air Resources Board

This project will be looking at the effects of drought on California’s wildfire frequency and intensity levels throughout the years 2000 - present. The data used to conduct this analysis will come from California’s Department of Forestry and Fire Protection Services (CalFire) and the United States Drought Monitor. This analysis will be diving into the yearly average acres burned from wildfires and the yearly average drought levels across California. We will be determining which areas of California are the most affected by the drought and increasing wildfires.

## Referenced data

U.S. Drought Monitor: https://droughtmonitor.unl.edu/DmData/DataDownload/WebServiceInfo.aspx
California’s Department of Forestry and Fire Protection Services (CalFire): https://www.fire.ca.gov/stats-events/



# Questions asked throughout this project
 • What are the average drought rates over time?

 • What is the count of our different drought rates from 2000 - presnt?

 • How is California’s drought altering wildfire frequency and intensity throughout California?

 • How do these drought patterns change over time and what levels of drought is CA experiancing?

 • How is California’s drought altering wildfire frequency and intensity throughout California?

 • Where are we seeing wildfires in CA and how big are these fires? 

# Figures 

Figure 1 

Figure 2 

### Drought Levels in CA from 2000 - Present
![Drought Levels in CA from 2000 - Present](https://github.com/aharris206/Project_01/blob/Maddy/Images/Drought%20Level%20over%20time_Final.png)

Figure 3 is displaying occurances of drought condiations over time. We can see more occurrences of extreme drought levels (Categories D2 - D4) occurring from 2015 - present compared to previous years. 


### California areas under drought conditions from 2000 - Present
![Area under drought conditions](https://github.com/aharris206/Project_01/blob/Maddy/Images/CA%20area%20in%20drought_Final.png)

Figure 4 shows the areas of CA experience the higher drought levels (Categories D2 - D4). We can see that there are more areas that experiance D2 - D4 levels of drought more often in 2012 - present.

![Area under drought conditions](https://user-images.githubusercontent.com/119692610/218214583-58f84772-86b7-4559-82f2-99ed0be0ae77.png)

Figure 5 shows the change in the average drought level in California over the 23 year time period. Lauren created this image using a dataframe that she created from calculating the mean Level ID of 2 year periods from the data source.

Figure 6

## Analysis 
- Overall we are seeing more wildfire occurrences while drought conditions are in severe (D2) to exceptional (D4), especially in Southern CA. 
- California has been averaging a higher drought level since 2015, than in the previous 10 years.
- We are seeing more wildfires and larger burn areas since 2015.

## Summary 
While there can be many factors affecting wildfires, with the data we observed, we believe there is a correlation between higher levels of drought and the frequency/intensity of wildfires in California. We observed that there were more wildfires, and more intense wildfires, in years that California was in a severe to exceptional drought level; therefore, we believe that drought does have an effect on the intensity/frequency of wildfires.

## Challenges
Throughout this project we faced a variety of challenges. The first challenge was finding data that could be used to analize how drought levels throughout CA effect wildfires. Orgininally our group wanted to analize preciputation levels across CA over the last 20 years. While looking into publically accessable databases that contained this type of information, we found data that would give us preciputation levels but did not have location of these events. Instead the information for "locations" was described as monitoring stations. From this we realized that the preciputation data would not work for our analysis. After this realization we decided to use the drought data to show how California is affected by the lack of preciputation. 

The second challenge was dealing with our data. For this project we found two sources of data, one being from U.S. Drought Monitoring (drought data) and the other from the California Department of Forestry and Fire Protection Services (Wildfire data). The data required heavy preparation in order to develop clean figures. For the wildfire data, each wildfire was reported as an event with a Coordinated Universal Time (UTC) stamp. We had adjust the data to bin the wildfires into yearly data so we could look at wildfires over time.  

## Tasks and Contributions

### Aster Harris - A couple of additions I added that may have been pushed to the main branch. 
I wrote the `fire_acre_burn.ipynb`, `fire_acre_burn_soCal.ipynb`, and `fire_data_graphs.ipynb` files which grabbed and plotted data off fire.ca.gov, turned the `ISO 8601` Timestamps it provided into `UNIX` Timestams in order to create a Months column via binning and saved them to CSV. *these can be seen in the `cleaned_csv` file under `Resources`*
I also wrote the `CSV_cleaner.ipynb` file as a group resource to aid us all in cleaning up some of our CSVs (:

### Maddy Gutieruiz
Developed the project proposal documentation, wrote project background, coordinated project tasks for team, found data used throughout the project, created figures 3 and 4, compiled figures and developed the presentation, and developed the README.file.

### Lauren Huffmire

### Sara Zhu

### Terry Goins

