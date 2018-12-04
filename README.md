<html>
<img src ="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Olympic_rings_without_rims.svg/1200px-Olympic_rings_without_rims.svg.png">
</html>
<br/>
<p align="center">
<font size="20" color="White" face="Trebuchet MS" style="border:2px solid DeepSkyBlue">120 Years of Olympic History</font>
</p>
<br/>
## This is a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016.
### The file contains 271,116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event.
<p align="left">
<font size="4">The dataset included:</font> 
</p>
```markdown
- ID: Unique number for each athlete
- Name: Athlete's name
- Sex: M or F
- Age: Integer
- Height: In centimeters
- Weight: In kilograms
- Team: Team name
- NOC: National Olympic Committee 3-letter code
- Games: Year and season
- Year: Integer
- Season: Summer or Winter
- City: Host city
- Sport
- Event
- Medal: Gold, Silver, Bronze, or NA
```
_Note that the Winter and Summer Games were held in the same year up until 1992. After that, they staggered them such that Winter Games occur on a four year cycle starting with 1994, then Summer in 1996, then Winter in 1998, and so on._
<br/>
<br/>
## We also pulled data from a Wikipedia page detailing the [2016 Summer Olympics Women's Marathon results.](https://en.wikipedia.org/wiki/Athletics_at_the_2016_Summer_Olympics_–_Women%27s_marathon)
### Time was the information that this dataset provided that was not included in the original dataset.
<p align="left">
<font size="4">The dataset included:</font> 
</p>
```markdown
- Rank
- Athlete's Name
- Nationality
- Time
```

<br/><br/>
<p style="border:2px solid Gold">
<font align="center" size="6" color="White">Questions</font><br/>
<font align="left" size="5">1. What factors contribute to the performance of an athlete?</font><br/>
<font align="left" size="5">2. How are athletes changing, per sport, over time?</font><br/>
</p>
### As a result of the size of our dataset we aimed to narrow our scope by focusing on the marathon specifically. This was the sport in which we analyzed the most extensively. Specifically, we make many comparisons between male and female athletes who competed in the marathon event.
<br/><br/>
<p align="center">
<font size="7" style="border:2px solid Tomato">Context Information</font>
</p>
<p align="center">
<img src="mens mar pic.jpg" width="75%"><br/>
<img src="london-2012-marathon.jpg" width="75%"><br/>
<font size="5">The men's marathon has been present on the Olympic athletics program since 1896, but the women's event wasn't added until ninety years later in 1984.</font>
</p>
<br/>
<p align="center">
<img src="first women marathon.jpg" width="75%"><br/>
<font size="3">Joan Benoit of the U.S. breaks away from the pack on her way to winning the first Olympic women's marathon during the 1984 Summer Olympic Games in Los Angeles.</font>
</p>
<br/>
<p align="center">
  <font size="5">Medal Counts by Country for Women's Marathon</font><br/>
  <img src="Screen Shot WOMEN.png" width="90%"><br/><br/>
  <font size="5">Medal Counts by Country for Men's Marathon</font><br/>
  <img src="Screen Shot 2018-12-03 at 10.13.46 PM.png" width="90%"/>
</p>
_The Unified Team was the name used for the sports team of the former Soviet Union at the 1992 Winter Olympics in Albertville and the 1992 Summer Olympics in Barcelona._
### These graphs show us the countries that are most represented in our future graphs that are broken down by medal type.
<br/><br/>
<p align="center">
<font size="7" style="border:2px solid Tomato">Answering our Questions</font>
</p>
<p align="center">
  <font size="5">Change in Average BMI Over Time for Men and Women's Marathon</font><br/>
  <img src="BMI NEW DOTS.png" width="90%"/><br/><br/>
  <font size="4">We reached our conclusions using the following calculation:</font><br/>
  <img src="BMI3.png" width="40%" hspace="20"/> 
  <img src="BMI Chart.png" width="40%"/>
</p>
### The mean BMI values would suggest that, despite the spike between 1900 and 1920, the BMI for men has been trending downwards. Women do not appear on the graph until 1984 when they were first allowed to race the marathon in the Olympics, but their mean BMI also shows a downward trend. Further analysis of the athelete's BMIs is to follow. 
<br/>
<p align="center">
  <font size="5">Height Distributions of Men and Women's Marathon Non-Medalists vs. Medalists (in centimeters)</font><br/>
  <img src="Height Dist of Non Medalists.png" width="45%"/> 
  <img src="Height Dist by Medal Type.png" width="45%"/>
</p>
### The average height for men running the marathon is 172 cm, or 5’ 7”. We can see that average height for men who medaled is 171 cm, which is slightly lower than the general average. The minimum height is 148 cm, or 4’ 10”, and the maximum is 200 cm, or 6’ 7”. 
### The average for women is 162 cm, or 5’ 4”. Like with the men, the average height is slightly lower for medalists at 161 cm. The minimum is 147 cm, or 4’ 10”, and the maximum is 183 cm, or 6’.
<br/>
<p align="center">
  <font size="5">Weight Distributions of Men and Women's Marathon Non-Medalists vs. Medalists (in kilograms)</font><br/>
  <img src="Weight Dist of Non Medalists.png" width="45%"/> 
  <img src="Weight Dist by Medal Type.png" width="45%"/>
</p>
### The average weight for men marathon runners is 60 kg, or 132 lbs. The average weight of men who medaled is almost exactly the same. The minimum weight is 42 kg, or 93 lbs, and the maximum is 106 kg, or 234 lbs.
### For women, the average weight is 49 kg, or 108 lbs. The average for women medalists is 48 kg, or 105 lbs, which is only slightly lower than the general average. The minimum is 35 kg, or 77 lbs, and the maximum is 67 kg, or 147 lbs.
<br/>
<p align="center">
  <font size="5">Age Distributions of Men and Women's Marathon Non-Medalists vs. Medalists</font><br/>
  <img src="Age Dist of Non Medalists.png" width="45%"/> 
  <img src="Age Dist by Medal Type.png" width="45%"/>
</p>
### For men, the average age of the marathoners is 28.85. The medalists average 27.7 years in age, which is slightly lower than the average. The minimum is 16 and the maximum is 52.
### The average age of women who ran the marathon is 30. Medalists average slightly younger, at 29 years. The minimum is 18 and the maximum is 48. We can see that on average, women marathoners are slightly older than men.
<br/>
<p align="center">
  <font size="5">BMI Distributions of Men and Women's Marathon Non-Medalists vs. Medalists</font><br/>
  <img src="BMI NEW NON MEDALIST.png" width="45%"/> 
  <img src="BMI NEW MEDALIST.png" width="45%"/>
</p>
### The average BMI for men is 20, which is in the normal weight range. The BMI of male medalists is similar. The minimum is 16, and the maximum is 31.
### For women, the average BMI is 18.6, which is only slightly higher than the underweight range. The medalists’ average is approximately the same. The minimum is 15.42 and the maximum is 26.2
<br/>
<p align="center">
  <font size="5">Women's Marathon Times vs. BMI at 2016 Rio Olympics</font><br/>
  <img src="BMI vs Time.png" width="90%"/> 
</p>
### While it is not clear from this summary, when we looked at finish times and BMI, we saw a slight correlation between the two. After looking at the data, we determined R2 to be .17, showing that 17% of the variation can be explained by linear regression. This shows that this correlation is most likely not statistically significant.
<br/><br/>
<p align="center">
<font size="7" style="border:2px solid Tomato">Summary</font><br/>
</p>
### This is only a rudimentary analysis of what best predicts a marathon athlete's success, as it is primarily based on height and weight, which were combined to calculate BMI, as well as age. We found that the average weight and BMI of medalists versus non-medalists does not vary much. Furthermore, we observed that medalists were usually only slightly younger and slightly shorter than the "average" participant. 
### However, there are many other factors that determine an athlete's success and make an elite runner stand out among the rest. These factors include, but are not limited to, training volume, body size, tendon function and the length and frequency of strides. One could also hypothesize that the country an athlete is competing for could have an effect on their performance because they may have differing levels of support and training.
