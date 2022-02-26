# An Analysis of Kickstarter Campaigns
## Overview of Project
The purpose of this project is to deliver an analysis to Louise regarding Kickstarter campaigns. There are two areas of focus within this analysis: 1. Theater Kickstarters with respect to launch date and funding goals, and 2. Plays with respect to outcomes. 
## Analysis and Challenge
The analysis started by utilizing a larger Kickstarter data set as the primary source. This larger data set included information about Kickstarters throughout multiple countries, years, and areas of interest.

The first step of the analysis was intended to understand the Theater outcomes based on launch date. A pivot chart and pivot table were created by using the larger Kickstarter data set on a subsequent tab within the Kickstarter Challenge workbook. The new tab was titled Theater Outcomes by Launch Date. The pivot table was created by placing Parent Category and Years within the filter section, while the Rows section contained Date Created Conversion. Lastly, both the columns section and the values section contained Outcomes. To arrange the table so outcomes displayed in an order where Successful was in the first column, the columns were arranged in descending order. In an effort to display only the information relevant to the analysis, filters were placed on Parent Category and the Outcomes. The Parent Category was filtered to only display Theater, while the Outcomes were filtered to only display Successful, Failed, and Canceled events. Subsequently, by way of updating the pivot table, the pivot chart was updated to reflect an image representative of the pivot chart. The pivot chart was saved as a png file titled Theater Outcomes v Launch within the Resources folder.

The second step of the analysis served to learn about a subcategory within Theater, Plays. A second tab within the Kickstarter Challenge workbook was created called Outcomes Based on Goals. 8 Columns were created from Cell A1 through H1 respectively labeled Goal, Number Successful, Number Failed, Number Canceled, Total Project, Percent Successful, Percent Failed, and Percent Canceled. Thereafter, rows were labled from A2 to A13 respectively with ranges of goal amounts from less than 1000 in increments of 4999 up to 50000 or more. The COUNTIF forumla was utilized in Cells B2 to D13 to count quantity of Plays that were Successful, Failed, or Canceled provided a specific goal range. Next the totals with respect to outcomes were quantified in Column E based on goal ranges.  the percents of each respective outcome were calculated using a percent


