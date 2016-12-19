
# Overview

This repo contains Lucid's polling data for the 2016 elections. Over the course of four months, we conducted over 71,000 interviews across 13 surveys. Like [most other pollsters](http://fivethirtyeight.com/features/the-polls-missed-trump-we-asked-pollsters-why/), our presidential tracker [got it wrong](https://luc.id/2016/11/09/how-could-we-have-been-so-wrong/). In the interest of research and transparency, we've decided to make our data publicly available. This polling was done in conjunction with our media partner, the New Orleans Times-Picyune.

Beginning August 1, 2016, we interviewed several hundred respondents per day as part of our daily presidential tracker. In October, we did 12 surveys in battleground states, each done over a period of a few days. The survey column (the first column in the data) will let you know which survey that particular response is from.

## Files

polling-data.csv - This contains the raw polling data. In addition to the raw data, we've appended the mapped questions and answers to save you a step.

questions.csv - This has the questions and answers, as they were presented to respondents. This file is unnecessary, as we've done the mapping for you. However, it may be helpful to some to see how the questions and answers were worded.

## Question Flow

We asked each respondent for their ZIP code, from which we derived their state.

Each respondent was then asked for their party affiliation. If they answered Republican or Democrat, we asked a follow-up question on the strength of their affiliation. If they answered independent, we asked if they lean closer republican or democrat.

Next, we asked if they were registered to vote and if they intended to vote in the upcoming presidential election. Any non-registered voter and those who did not intend to vote were excluded.

We then ask the respondent how they planned on voting in the presidential election. If they responded that they were unsure, we asked the "leaner" question. The same logic was applied to the senate question, based on the respondent's state.

At the end of the survey, each respondent was asked their age, gender, ethnicity, education level, and household income. 

## Misc. Notes

On September 2 through 5, the tracker was accidentally turned off, thus we are missing data from those days. Oops.

We've published this data without our weights. However, you can find that information on [our methodology page](https://luc.id/2016-presidential-tracker/) and a PDF is available for each day with that individual day's weights.

## Contact

If you have questions about our raw data or would like more information on our product please contact Andrew Dunn (adunn@luc.id) and Eli Ackerman (eackerman@luc.id). If you have any interesting insights or thoughts, or do something cool with this data, we'd love to hear about it.

To learn more about Lucid or if you want to join our team to work on cool data problems, check us out at www.luc.id.