# The Effect of State Electric Vehicle (EV) Rebate Policy on EV Registration

## Introduction
Electric vehicles (hereafter, EV) have been moving into the spotlight in the recent years. The technology associated with manufacturing electric vehicles has significantly been advanced, bringing in more sales. Additionally, some states began offering rebates for purchasing EV’s which may have led to an increase in sales. We seek to quantify the effect of state rebates on EV sales. This analysis will shed light on the effect of state policies to increase EV sales and protect the environment. 

For our backward design project, we aim to seek the effect of state rebates in EV sales. Our team attempts to quantify the effect of state rebates by comparing EV sales between states that gave financial rewards and states that did not offer any type of rewards in purchasing EVs. 

## Project Design
To assess the effectiveness that state incentives  had on electric vehicle sales, we believe a difference in difference analysis would be the most effective study.  Our data is a time series dataset stretching from 2002 to 2018 capturing every new electric vehicle registration in a given state. By aggregating every registration by year, we can determine how many new electric cars were purchased for that state.  We can then use this annually aggregated data to compare two states, one that had policy implemented to give monetary incentive and one that did not. California and New Jersey are two such states. In 2010, California launched the clean vehicle rebate program which offered up to $7,000 dollars for the purchase or lease of new, eligible zero-emission or plug-in hybrid light-duty vehicles. New Jersey had no such incentive plan. 

There is a clear delineation in time when we can say the treatment effect took place. This policy went into effect in 2010, which aligns well with our data.  We have eight pre-treatment years from 2002 - 2009, and nine post-treatment years from 2010 - 2018.  This gives a solid amount of data for both pre and post treatment, and gives us a strong counterfactual with New Jersey having the same data over the same time period. Electric vehicle sales have almost certainly been rapidly increasing over this time period regardless of monetary incentive, so based upon the data we may have to explore options such as the log of electric vehicles sold, but despite this we hope to see a fairly clear shift up in the purchase of electric vehicles after 2010 in California relative to the trend in New Jersey after 2010.

## Data Sources
- Atlas EV Hub
- US Census
- US Energy Information Administration
