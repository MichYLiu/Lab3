# Lab3
---
title: "DataVis"
output:
  pdf_document: default
  html_document: default
  word_document: default
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Data Vistualization Warmup


![NYT Article Graph](DataVisGraph.png)

The data that I am visualizing is a graph from a New York Times article that is looking at how often water filtration companies violate health standards set by the government. The graph is specifically looking at how living in different places can change the quality of your water by measuing how many times the water purification companies were in violation of new water quality regulations.

The graph, which comes from Allaire, Wu, and Lall, PNAS, looks at the number of violations per 100 water systems from 1985 - 2018 and graphs it in a line plot based off of where the community is located: rural low income communities, rural high income communities, suburban, and urban commpanies.

This graph helps show me how likely the water treatment center near me is going to violate new water quality regulations, with low income rural families being more at risk of unsafe water compared to urban families.

The visualization did really well in organizing the data and making the greaph very clean, because it is very easy to look at the graph and get a lot of information out of it. However, both the urban and the subburban colors on the graph were basically the same light grey shade that made it very hard for me to see and tell the difference between them. Additionally, the graph only showed the different income levels for rural communities but didn't show the distinction between high and low income families in suburban or urban communities. While the author probably did that to prevent the graph from getting too crowded and filled with too many things, this also means that we are getting a biased perspective of the data.
