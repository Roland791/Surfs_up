Overview of the analysis: Explain the purpose of this analysis.
Results: Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.
Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.

surfs_up


##Overview of analysis
The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. The way we get the temperature data is by running seperate queries for the months of June and December. Query data is stored in a list then converted to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method. Here is what we found:

##Results

![June Tempertures](https://github.com/Roland791/Surfs_up/blob/main/Images/June_Temps.PNG)


-- In June we had a total count of 1700, mean of 74.9, min of 64.0 and max of 85.0

![December Tempertures](https://github.com/Roland791/Surfs_up/blob/main/Images/Dec_Temps.PNG)

-- In December we had a total count of 1517, mean of 71.0, min of 56.0 and max of 83.0

Screen Shot 2020-09-18 at 7 16 24 PM

-- Standard deviation is 3.25 in June and 3.75 -- making a .5 difference in the two different seasons

##Summary
From our data we can tell what our temperatures are but since there are other attributes to the weather such as precipitation it shows that we can run additional queries to let us know whether or not people can come and visit the shop. If we are able to gain more data for the area we can run even more queries! From there we can decide how we would like to build the shop and what areas would make this a more prominent location for visitors to come.

© 2021 GitHub, Inc.