###Proposal
####Eden Zik and Kahlil Oppenheimer 
==========
Click here to view the proposal:
[![PDF Status](https://www.sharelatex.com/github/repos/edenzik/128Project/builds/latest/badge.svg)](https://www.sharelatex.com/github/repos/edenzik/128Project/builds/latest/output.pdf)


#####Summary:
Data analysis tools are extremely high in demand. However, one
known issue with data analysis is an inconsistency in formatting
between different data sources. Is my data compatible with the
analysis tool I’m trying to use? This problem is only exacerbated
when data is represented inconsistently between various mediums.
Take for example a team of two, each trying to represent
the same structured data. Let’s say that one person decided to
create an Excel spreadsheet while the other wrote a Python script
to populate a CSV file. What if they chose inconsistent names of
attributes for enumerated types (i.e. “female” vs. “f” vs. “Female”)?
What if one person decided to leave some cells blank,
while the other didn’t? What if the person entering into Excel
had typos that were corrupting various aggregation results? Suddenly,
the team’s simple task of trying to merge and aggregate
their data with some analysis tool becomes much more complicated.

To deal with this, many analysts spend a significant amount writing
various scripts to transform multiple data sources into one
standard. This “data wrangling” often requires manual transformations
of columns and rows, correcting individual values,
and aggregating data from multiple sources with different layout.
Fortunately, two applications were created to aid this process
along: Stanford’s Data Wrangler and Google’s Open Refine.
Although both projects have been developed with a similar goal
of a visual and intuitive interface for data wrangling, they create
a short-term but not scalable solution. Both Data Wrangler
and Open Refine export their “wrangled” result as one massive
CSV file. This is fine for small-scale individual tasks, but this
does not scale in the way that the modern world demands that
data scale. Our project will take this output CSV and transform
it into a specifiably normalized SQL relational database. This
transformation will allow the user all of the well-known benefits
of a relational database management system, such as referential
integrity, data consistency, and easier compatibility with analysis
tools. Our project aims to provide data analysts with the ultimate
tool for normalization of structured but unwrangled data.
