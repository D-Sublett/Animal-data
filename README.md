# Animal-data
For this project I decied to examine the differnce between reports of animals intake and animals euthanized in the US.I love animals and have worked at many shelters so I thought that this would be interesting to look at. 

Problems faced: 
In gathering the data I ran into several problems. Many of the places I looked for the data did not report if the stats were from the US and/or what year they were from. In some cases the stats were from all different years which made it hard to find any conneciton. In addion non of the sites reported the same kind of stats making it challenging to find information to examine. After gathering the data the best I could I noticed several gaps in information. 

source	           animals adopted	    intake	          # euthanized	       year
ASPCA	              3.2 mil       	    6.5 mil         	1.5 mil            	N/A
Bestfriends.org	    N/A	               5.4 mil	          625,000	            2019
Humane Society	    4 mil	              6-8 mil          	3 mil	              2021
Petpedia.co		       N/A                6 mil	            625000	            2021


Above is the originally gathered data.

Due to inconsistancies I cut the year  and animal adoption collumn. I also changed the humane society intake to 7 as a median. 

![Cleaned data](https://github.com/D-Sublett/Animal-data/blob/main/Capture3.PNG)

This is the cleaned data. To analyze the above data I then tried to make a scatter plot that did not produce viable results. The numbers were skewed and the visual was confusing.
![Failed graph](https://raw.githubusercontent.com/D-Sublett/Animal-data/main/Capture.PNG)
This is the failed visual. As you can see, the Y axis is not in an understandable format which makes it appear as though shelters that intake fewer animals euthanize more.

After the failure of the scatter plot I decided to try a bar chart. This visual did produce viable results. said charts are included below

![Intake](https://github.com/D-Sublett/Animal-data/blob/main/intake.PNG)
![Euthanized](https://github.com/D-Sublett/Animal-data/blob/main/Euthanized.png)

In examining the two visuals you can see that the shelters intake more then the euthanize. At first glance the humane society appears to intake and euthanize a similar amount however the y axis under examiniation shows that they do not. They intake the most animals thus they also euthanized the most however the intake is still higher then the euthanized. That said, I have no idea if the intake and euthanized stats come from the same year as that information was not provided. Knowing this fault in the data, they could not be further analyzed for comparrison or corrolation as the results still would not be viable in any sense. 

Overall I would say the data gathered is rather useless. Without the dates to compare the numbers these stats could be from very different years and thus not viable for comparison. In additon, there is a lot of missing information of how these stats were aquired as the sites not only included no stat dates, page published dates, as well as citations from where the stats came from. This makes the data gathered unreliable. In trying to replicate this, unless they used the exact data I gathered, there is a large margin for error due to the haphazard manner the stats were found. To reproduce this analysis with viable results you would have to ensure that the data collected was dated and covered the same locations. Then you could do comparrisons to what different shelters reported as happening in the US to see if there are discrepencies and/or examine the intake and euthanized rate over several years to see if there is a corrolation and/or an growth or decline in the number.


