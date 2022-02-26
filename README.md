# An Analysis of Kickstarter Campaigns
## Overview of Project
The purpose of this project is to deliver an analysis to Louise regarding Kickstarter campaigns. There are two areas of focus within this analysis: 1. Theater Kickstarters with respect to launch date and funding goals, and 2. Plays with respect to outcomes. 
## Analysis and Challenge
The analysis started by utilizing a larger Kickstarter data set as the primary source. This larger data set included information about Kickstarters throughout multiple countries, years, and areas of interest.

The first step of the analysis was intended to understand the Theater outcomes based on launch date. A pivot chart and pivot table were created by using the larger Kickstarter data set on a subsequent tab within the Kickstarter Challenge workbook. The new tab was titled Theater Outcomes by Launch Date. The pivot table was created by placing Parent Category and Years within the filter section, while the Rows section contained Date Created Conversion. Lastly, both the columns section and the values section contained Outcomes. To arrange the table so outcomes displayed in an order where Successful was in the first column, the columns were arranged in descending order. In an effort to display only the information relevant to the analysis, filters were placed on Parent Category and the Outcomes. The Parent Category was filtered to only display Theater, while the Outcomes were filtered to only display Successful, Failed, and Canceled events. Subsequently, by way of updating the pivot table, the pivot chart was updated to reflect an image representative of the pivot chart. The pivot chart was saved as a png file titled Theater Outcomes v Launch within the Resources folder.
https://github.com/mshedlosky/Kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png

The second step of the analysis served to learn about a subcategory within Theater, Plays. A second tab within the Kickstarter Challenge workbook was created called Outcomes Based on Goals. 8 Columns were created from Cell A1 through H1 respectively labeled Goal, Number Successful, Number Failed, Number Canceled, Total Project, Percent Successful, Percent Failed, and Percent Canceled. Thereafter, rows were labled from A2 to A13 respectively with ranges of goal amounts from less than 1000 in increments of 4999 up to 50000 or more. The COUNTIF forumla was utilized in Cells B2 to D13 to count quantity of Plays that were Successful, Failed, or Canceled provided a specific goal range. Next the totals with respect to outcomes were quantified in Column E based on goal ranges. The percent of each category was calculated by dividing the quantity of each category by the total with respect to a given goal. In order to prevent errors, the IFERROR formula was used.
https://github.com/mshedlosky/Kickstarter-analysis/blob/main/Outcomes_vs_Goals.png
##Results
There are a couple conclusions that can be drawn from the Theaters data based on Launch Date. Firstly, May is the most favorable month to perform a Theater Kickstarter. The second conclusion is that December is the least favorable month to start a Theater Kickstarter.

With respect to the Play outcomes based on goal, there is a greater than 50% chance that a Play Kickstarter will have a Successful outcome if the goal is set to less than $20,000.

While the above conclusions can be made, there are limitations of the data. It is not understood where this data is collection from and the method of collection. Further, there is no demographic data regarding the contributors such as income, age, ethnicity, zip code, and other items that may impact the outcomes. By not including such information, the results produced have the potential of reflecting bias. 

Other tables and charts that could be created to provide further insight would be charts related to Plays broken down by regions

