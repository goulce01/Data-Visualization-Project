<html>
  <img src ="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Olympic_rings_without_rims.svg/1200px-Olympic_rings_without_rims.svg.png">
</html>

# 120 Years of Olympic History 
<br/>
## This is a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016. 
### The file contains 271,116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event. 
<br/>
**The dataset included:**
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
<br/>
**The dataset included:**
```markdown
- Rank
- Athlete's Name
- Nationality
- Time
```
_Time was the information that this dataset provided that was not included in the original dataset._
<br/>
<br/>
## The questions we tried to answer were as follows:
```markdown
1. What factors contribute to the performance of an athlete?
2. How are athletes changing, per sport, over time?
```
<br/>
Our first visualization examines 

![Image](data:image/png;base64,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)

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Number
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/goulce01/DataVisualizationProject/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
