# kickstarter-analysis

# Kickstarting with Excel

## Overview of Project

This project is to help Louise get a more insightful look into the kickstarter funding campaigns of others who seeks out similar funding amounts for their plays, so that she is more prepared for her own play's campaign. 

### Purpose

Included in this project are kickstarter data, along with visualized data trends on Outcomes based on Launch Date for the "Theater" parent category and Outcomes based on Goals for the "Plays" subcategory. These uncovered data trends will help us and Louise better understand how Launch dates and Goal amounts will affect the successes and failure of a campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

We have a Pivot table here created with the data for the "theater" parent category. These data consists of a breakdown on the various months that campaigns are launched in and how they trend for successes, failures and cancelations in a marked line chart. The dataset can be filtered for inidividual year's look as well if necessary.

<img src=“.//resources/Outcomes_vs_Goals.png”></img>

### Analysis of Outcomes Based on Goals

The Outcomes Based on Goals dataset has all the "play" subcategory entries categories into goal targets from "Less than 1000" all the way up to "Greater than 50000" with intervals at every 4999 after 5000. These are counted up for "Successful", "Failed" and "Canceled" columns and then added together to find each goal categories' totals. We further delve into the data by looking at the outcomes as a percentage and then charting them with a line chart to see if there are correlations between the asked goal amounts and their outcomes.


### Challenges and Difficulties Encountered

Data on "Theater Outcomes By Launch Date" does not seem to be as complete as initially thought when looking at it as a whole (all years). Looking into individual years shows that years other then 2014, 2015 and 2016 looking a little lackluster in terms of data points, which might not be as accurate of a dataset as initially thought.

Data on "Outcomes Based on Goals" seems to be skewered towards the lower end numbers here as the goal category for Louise falls under around just 15% of the total entries in the dataset. A bigger sample might be needed for more accurate views of these trends.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Two main conclusions that can be understood from looking at Outcome data ased on Launch date is that there is a big uptick in successes for plays that launched in May, showing that May is the best month to start a campaign. On the other hand, December seems to be the worst time to start a campaign, being the end of a downward trend in successes for the rest of the year. Successes seems to be overall the case here when looking at just the "Theater" parent category as this encompasses 61% of the campaigns.

- What can you conclude about the Outcomes based on Goals?

Outcomes based on goals for plays seem to succeed far more when goal fundings are below $5,000 or within $35,000 to $44,999. On the flip side, kickstarters seem to fail around $15,000 onwards all the way until $34,999. Kickstarters for plays also seem to last the entirety of their deadline, without a single campaign cancelling regardless of the funding goals.

- What are some limitations of this dataset?

The biggest flaw in this dataset is that there are no details for the usages of the fundings itself. Although it is useful to know the successes and failures of kickstarters goals and pledged amounts are at, it is equally important to know where the fundings are allocated to within the campaign. A percentage breakdown of the fundings for the campaign or even just a short description for this would have made this dataset significantly better for analytics.

- What are some other possible tables and/or graphs that we could create?

Other possible tables and/or graphs that could be created are "Percentage of Successful campaigns vs Failed campaigns" for every Parent category of the kickstarter data which can be displayed neatly in a stacked divergent bar chart. This type of chart really highlights the positive and negatives of a subject in order to give meaningful insights on how the 2 outcome rank against each other. A possible immediate usage would be for investment firms who are looking for their next business opportunities, this shows how popular a particular category would be along with their successes and failures when it comes to seeking funding from others, therefore bringing up immediate risks and benefits when considering an investment.
