---
title: "MPSA 2022 Presentation: A Shift in Jewish Voting Behavior in the 2020 Presidential Election"
subtitle: "This is a brief overview of the research conducted, not the completed paper."
summary: An informal look into my undergraduate thesis on Jewish voting behavior, specifically relating to Jewish voters and Donald Trump's rhetoric.
tags:
  - ElectionSci
date: '2023-07-30T00:00:00Z'
draft: false
reading_time: true

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Made with Canva
  focal_point: Smart

links:
url_code: ''
url_pdf: '/Users/paytonlussier/Desktop/portfolio_wwebsite/assets/media/Lussier_Thesis_2022 copy.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

### **Introduction**

For the purposes of my undergraduate thesis, I decided to take a look into voting behavior in my home state of Florida. In both 2008 and 2012, Barack Obama carried the state followed by two victories for Donald Trump. Everyone was, and is still, asking; What happened to Florida? In an attempt to gain insight into that answer, I decided to look at my own community of Jewish-Americans. I hypothesized that Donald Trump's rhetoric surrounding Israel would have an effect on Jewish voters in South Florida. To achieve this, I used the state voter file and precinct level data to compare voter turnout and vote choice in highly populated Jewish areas. 

### **Key Background Information**

In 2021, Pew Research Center published an in-depth report on Jewish-Americans in the United States. The report found that a majority of Jewish-Americans state they have "a degree of emotional attachment [to Israel]". I sought to understand how influential this attachment would prove to be in the frame of politics and candidate choice. Throughout his presidency, Donald Trump made clear attempts to capitalize on the growing support for Palestinians within the Democratic party, in an attempt to frame himself as the true "Pro-Israel Candidate".

Before any analysis, I looked into the historical connection between the Jewish people and the political left. As of 2019, 70% of all voting age Jews were registered Democrats. Dr. Kenneth Wald's book, The Foundations of American Jewish Liberalism, aims to explain this phenomenon through a series of possibilities, many focusing on the long history of discrimination and abuse that the Jewish people faced. Wald also frames the 'rise of the religious right' in the 1980s as a potential direct threat to religious equality within the country. 

### **Donald Trump and Israel**

Unsurprisingly, Donald Trump's controversial nature did not halt at the doorstep of the Jewish community. American-Jewish groups have cited him as both antisemetic and philosemetic. During his time in office, his administration led a number of policies that were viewed favorably by the Israeli government that in the lead up to the 2020 U.S. presidential election, 63% of Israeli citizens supported him. This fact is made more interesting given that prior to the 2016 election, Hilary Clinton was the candidate slightly favored in the country.

### **Research Design** 
To conduct my study, I utilized the Florida Division of Election's Election Recap files following the 2020 General Election for Miami-Dade, Broward, and Palm Beach counties. I introduced a dichotomous variable into the data from which indicated whether or not the individual had been born in Israel. The data was then aggregated from the individual-level to the precinct-level to determine the percentage of the precinct that was Israeli-born. 

I also used the Precinct-Level Results files for the 2020 and 2016 General Elections in the three same Florida counties. This determined the vote share for the Republican and Democratic candidates which was merged with the aggregated Israeli-born data by the unique precinct identifier code. An additional dichotomous variable was introduced to determine whether or not the precinct was greater than 2% Israeli-born. This variable was how I compiled my conservative sample of high Jewish areas. This left me with 20 precincts of interest. 

![screen reader text](Miami.png "Figure 1: Israel-born Precincts > 2% (Miami-Dade County)")
![screen reader text](Broward.png "Figure 2: Israel-born Precincts > 2% (Broward County)")
![screen reader text](Palmbeach.png "Figure 3: Israel-born Precincts > 2% (Palm Beach County)") 

### **Findings** 
I ran OLS regression models that include demographic information at the precinct level in the 2016 and 2020 General Elections, including percentage of Israel-born. These models consider race/ethnicity, gender, and party affiliation. We see in the Table 1 below that our coefficient of interest, percent of Israel-born, appears as positive and statistically significant at all usual alpha levels. As the percentage of Israel-born increases by one percentage point, Trump support within a precinct is expected, on average, to increase by 0.795% in 2016 and 2.243% in 2020. As the percentage of Israel-born increases in a precinct by one, support for Trump increases by 1.44 percentage points from 2016 and 2020, all else constant. Figure 4 helps to further visualize the coefficients in Table 1. Percent Israel-born, despite having a large standard error, still represents the largest statistically significant coefficient of the demographic categories.

![screen reader text](regression.png "Table 1: Percent Support Trump, Precinct-Level") 

![screen reader text](coefficients.png "Figure 4: Coefficients for Change in Trump Support ")

### **Discussion** 
Literature and research continue to point towards American-Jewish alignment with the Demographic Party although perhaps with alignment is not as secure as it once was. We find that amongst South Florida counties, the percentage of Israel-born voters was a strong positive indicator in support for Trump. Not only did we find support for our expectation, as noted, we find that support increased 1.44 percentage points, on average, per every 1 percentage point increase in the Israel-born precinct population between the 2016 and 2020 General Elections. If anything, our findings showcase the potential for an ideological schism within the Jewish-American community due to the political polarization surrounding Israel. Our findings call into question that it is not the Jewish-American community writ large who embraced Trump following his victory in 2016, but a select sub-group who valued Trump’s rhetoric in support of Israel. The greatest limitation to this study is the lack of individual-level data for analysis. 

In conclusion, our results on the choices of heavily Jewish enclaves in South Florida precincts in the 2020 General Election show that those precincts with high concentration of Israel-born voters were more likely to support Trump in 2020 compared to 2015. We cannot determine if this is a trend that will persist past Trump’s time in the national spotlight or if it is a minor, circumstantial moment in American politics. Either way, drawing on an unique data set, our study shines some light on Jewish political behavior in the 2020 General Election.
