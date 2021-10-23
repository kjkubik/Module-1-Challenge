# Module-1-Challenge
### Deliverable 1: Outcomes Based on Launch Date Chart 
### Deliverable 2: Outcomes Based on Goals Chart 
### Deliverable, 3: A written analysis of the results (README.md)

# Kickstarting with Excel

## Overview of Project
Given the Kickstart site's campaign data, analysis was completed to find 
expected outcomes for a customer so that they could make informed decisions 
about their own campaign.

### Purpose
The Kickstarting Analysis was completed so that conculsions could be made about
outcomes of campaigns using science and mathematics practices. 

## Analysis and Challenges
The goal was to summarize outcomes using the variables found in the Kickstarter table. 
The primary data columns were: category, subcategory, outcome type, campaign start date,
country and goal amount.

To summarize the data, pivot tables and charts and statistical tables were created
so that specific outcomes could be seen. We also used several other Excel functions 
so that data could be utilized. 

### Functions used: 
```
- DATE(), YEAR()
- conversion of epoch date to readable: DATE(1970,1,1) + [epoch date])/60/60/24
- COUNTIFS()
- VLOOKUP()
- AVERAGE(), MEDIAN(), MODE(), STDEV.P(), QUARTILE.EXC()
- ROUND()
- IF(), IFERROR() and nested if statements
- percentage (=x/y*100)
```

### Other Resources used:
##### How to [Convert Epoch Dates to Readable Dates](https://www.epochconverter.com/)			
##### Understanding [Timestamps](https://websiteseochecker.com/blog/what-is-timestamp/)			


### Analysis of Outcomes Based on Launch Date
In this analysis, it was necessary to create a pivot table containing theater outcomes by month. 
We also created a line graph to visualize the pivot table results. 
 
### Analysis of Outcomes Based on Goals
In this analysis, we needed to show play outcomes broke down in goal amount ranges. In the columns, 
we needed to display the counts and percentages of the successful, failed and cancelled plays. We 
were also required to get a Total count of all three outcomes displayed.  

Lastly, I left my percentages with two decimal points in the table. It is bad practice to leave 
percentages in a format that confuses the reader. The last row of the table presents an issue. 
The totals should add up to 100%. They don't. When left rounded with no decimal points, they add 
up to 101%. 

### Challenges and Difficulties Encountered
The nested if statement is cumbersome and very difficult to debug within Excel. Also, within any
other language, you wouldn't do this. You would write a CASE statement. 

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?
  1) The month of May seems to be a very good month to launch a play campaign. 
  2) The months having an “R” in them have the greatest likelihood of failing play campaigns. 

### What can you conclude about the Outcomes based on Goals?
  1) The percentage of successful campaigns in the play sub-category have a goal of $5,000 or less. 
  2) The play campaigns with a high percentage of failure were over $25,000. 

### What are some limitations of this dataset?

### Whether Weather Matters

The data doesn’t answer some obvious questions. This leaves me wanting. 
The most obvious to me is the weather. By adding countries in southern 
hemisphere, we might be able to show the effect weather has on a 
successful campaign. 

The reason I believe this is because some four-letter words matter 
(**SNOW, HEAT, RAIN, FALL, WIND**). That is, it has been proven 
weather does matter in many well know studies. It has been used to 
prove humans commit crimes more in the summer, when there is **HEAT**. 
We also have used in studies to know when more babies are born. 
It is in the **FALL** we ‘shack-up’ to make babies. We have also 
used it to study depression. We know when the **SNOW** is falling, 
depression can leak easier into our lives.

### Other Limitations

Wouldn’t it have been nice to know what the MIN and MAX contribution 
of each subcategory was? How about whether there was other advertising 
or insentive utilized to promote the campaigns? 

### What are some other possible tables and/or graphs that we could create?

I would like my graphs to show a story. What kind of story could be told 
if we used deadlines? We have explored the length of a campaign as having 
the effect on outcomes. Looking at the deadlines to see if they might be 
an outcome factor might prove to be of some worth.

Also, we never touched on staff pick and spot light? Do they present an 
effect on outcome? Possibly. We will not know unless we explore them.

(https://images.search.yahoo.com/images/view;_ylt=AwrExo.PZXNh7x0A1yuJzbkF;_ylu=c2VjA3NyBHNsawNpbWcEb2lkA2Y4NTJjOGMzNGNmYTA4ZTVjYTk5NGIyNzRkM2YyMjhlBGdwb3MDNzAEaXQDYmluZw--?back=https%3A%2F%2Fimages.search.yahoo.com%2Fsearch%2Fimages%3Fp%3Dthe%2Bshow%2Bmust%2Bgo%2Bon%26type%3DE211US1487G0%26fr%3Dmcafee%26fr2%3Dpiv-web%26nost%3D1%26tab%3Dorganic%26ri%3D70&w=2000&h=366&imgurl=assurityconsulting.co.uk%2Fassets%2FSeminar-Logo-Images%2Fa2332f1d2c%2FShowMustHeader2k.jpg&rurl=https%3A%2F%2Fassurityconsulting.co.uk%2Fknowledge%2Fseminars%2Fthe-show-must-go-on&size=444.7KB&p=the+show+must+go+on&oid=f852c8c34cfa08e5ca994b274d3f228e&fr2=piv-web&fr=mcafee&tt=The+Show+Must+Go+On+CPD+Seminar&b=61&ni=21&no=70&ts=&tab=organic&sigr=mlw4QygdI9G.&sigb=2l8jMbsgERSB&sigi=P6GM2O3o.4QG&sigt=EFkHJtS6_isM&.crumb=8.n2kwSr7eb&fr=mcafee&fr2=piv-web&type=E211US1487G0)
