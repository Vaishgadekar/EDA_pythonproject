# EDA_pythonproject

# In this notebook you will find:

You will see simple statistics for data in Global Terrorism Database. For example, central tendency, dispersion and shape of a dataset’s distribution.
You'll see a lot of graphics and analysis customized by using data on terrorist attacks. You will find reviews of these analyses and graphics.
You will see the comparisons made to achieve some results and the frequency of terrorist attacks according to the specified years.
You will see which type of attack is used most in terror attacks, and how many deaths each one of these types of attack has caused.
Finally, through all the data, you'll see which country and how many people were killed in terrorist attacks

## Introduction

According to the FBI, international terrorism is defined as "violent, criminal acts committed by individuals and/or groups who are inspired by, or associated with, designated foreign terrorist organizations or nations (state-sponsored)".

The purpose of this analysis is to discover what trends in the data there are and what it can tell us about global terrorism attacks in terms of where they occur, the types of terrorist attacks, what weapons were used, who the terrorist targets are, and who the largest terrorist groups are.

### The variables of interest in this analysis are:

- Year: Year the attack took place (1970-2017 is the range)
- Country: Country the terrorist attack took place in Region: 
- Region the terrorist attack took place in 
- City: City the terrorist attack took place in
- Attack Type: How the terrorist attacked the victim
- Weapon Type: Weapon used by terrorist to attack
- the victim Target: Who the target of this terrorist attack is 
- Affiliation: What terrorist group is the terrorist part of

### About the dataset:
Global Terrorism Database is maintained by the National Consortium for the Study of Terrorism and Responses to Terrorism (START) at the University of Maryland.

Information about data stored in fields mainly used in this EDA[1]:

iyear: This field contains the year in which the incident occurred.

imonth: This field contains the month in which the incident occurred.

iday: This field contains the day in which the incident occurred.

country_txt: This field identifies the country or location where the incident occurred (categorical).

region_txt: This field identifies the region in which the incident occurred(categorical).

provstate: This variable records the name (at the time of event) of the 1st order subnational administrative region in which the event occurs.

city: This field contains the name of the city, village, or town in which the incident occurred.

attacktype1_txt: 1:Assassination 2:Hijacking 3:Kidnapping 4:Barricade Incident 5:Bombing/Explosion 6:Armed Assault 7:Unarmed Assault 8:Facility/Infrastructure Attack 9:Unknown.

targtype1_txt: Names of targtype1.

targsubtype1_txt: Names of targsubtype1.

gname: This field contains the name of the group that carried out the attack.

weaptype1_txt: Names of weaptype1.

### CONCLUSION:
- the most common type of terrorist weapons used are Bombing/Explosions, followed by Armed Assault, and Assassinations. The reason that bombings/explosions are the most common type of terrorist attack is likely due to how the information to make bombs is easily available, it is easier to use a bomb or explosive than attempt things like armed assault or assassinations, as well as the fact that there aren't things like background checks when it comes to getting a bomb as opposed to trying to get a firearm or get close enough to assassinate someone important.

- top 5 cities with terrorism attacks are Belfast, Baghdad, Karachi, Lima, and San Salvador. It is surprising to see that Belfast, Ireland is the top city for terrorist attacks since according to the interactive map we just created, Ireland isn't one of the countries with the highest terrorist attacks

- terrorist groups are the ISIL, Taliban,Shining Path and Al-Shabaab.

- South Asia, the Middle East & North Africa, Sub-Saharan-Africa, and South America have the most terrorism attacks. There is also a trend that the Western countries tend to have less terrorism attacks than the 3rd world countries. It is also not surprising to see that regions like South Asia, Middle East, Africa, and South America are the top ranking in terms of terrorism attacks due to the large disparities in wealth, differences in religions, as well as territorial disputes over oil.

-  increase in terrorism during the 2000's as opposed to 1970-2000. 2014 had the most terrorist attacks. The biggest increase in terrorist attacks is from from 2011-2014 and that after 2014, the number of terrorist attacks is decreasing.

- The Middle East and North Africa are seen to be the places of serious terrorist attacks. In addition, even though there is a perception that Muslims are supporters of terrorism, Muslims are the people who are most damaged by terrorist attacks. 

- 84% of the terrorist attacks in 1970 were carried out on the American continent. In 1970, the Middle East and North Africa, currently the center of wars and terrorist attacks, faced only one terrorist attack.




VIDEO LINK:https://www.linkedin.com/posts/vaishali-datascientice-ame_mippsoct2022-mippsoct2022-codersready-activity-6994964229170573312-dCog?utm_source=share&utm_medium=member_android
