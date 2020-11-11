# Communicate Data Findings - Fligth Data Final Project

This project is the final project for the Udacity Data Analyst Nanodegree.

## Installation

The following packages are necessary to correctly run/view this project:
Seaborn
MatplotLib
Numpy
Pandas
Datetime

## Usage

This project is specifically designed to examine Flight data (one of the recommended data options)
for the final data visualization portion the Data Analyst Nanodegree. It focuses on flight data from
1988 and 2007 and further wrangled it to examine only flights to and from Pittsburgh, PA. 
These choices were made related to the Analyst/Author's personal investment in these years and the city.

## References

As mentioned in the project itself, some external resources were utilized in solving problems related to
data wrangling and data visualization for this process. The following were notable references beyond
general utilization of package documentation:

- Credit to https://stackoverflow.com/questions/54313461/pandas-convert-float-to-proper-datetime-or-time-object
- Credit to https://stackoverflow.com/questions/13682044/remove-unwanted-parts-from-strings-in-a-column
- Credit to https://stackoverflow.com/questions/8248467/matplotlib-tight-layout-doesnt-take-into-account-figure-suptitle
- Credit to https://stackoverflow.com/questions/13228254/subplots-are-overlapping-axis-labels
- Credit to https://stackoverflow.com/questions/30228069/how-to-display-the-value-of-the-bar-on-each-bar-with-pyplot-barh
- Credit to https://stackoverflow.com/questions/45923189/remove-first-character-from-pandas-column-if-the-number-1

Other problems, questions, or simple solutions were sometimes referenced to the content provided in the Udacity
lessons themselves. In particular, the creation of the multivariate plots was based on examples from the coursework.

## Takeaways

The key takeaways from this exploratory analysis are the following (in no particular order):

- There were substantially more flights (over 2x more) in 1988 in Pittsburgh than in 2007
- Despite the vast difference in numbers, the overall pattern remaind fairly consistent when looking at flight data by month or by day of the week
- Summer travel was preferred over the Winter months and February was the least preferred month to travel
- Weekdays were preferred for travel over weekends and Saturday was the least favorite day for a flight
- Late Aircraft delays caused many delays for flights in and out of Pittsburgh in 2007
- No day of the week saw a lot more total delay time when for the top 5 delay types, but unsurprisingly, weekdays experienced more total delay time than weekends - likely due to the increased travel

The project contains additional data insights that go deeper than the above 6 