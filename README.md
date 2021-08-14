Overview of the analysis: Explain the purpose of this analysis.
Results: Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.
Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.

surfs_up


##Overview of analysis
The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. The way we get the temperature data is by running seperate queries for the months of June and December. Query data is stored in a list then converted to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method. Here is what we found:

##Results

![June Tempertures](https://github.com/Roland791/Surfs_up/blob/main/Images/June_Temps.PNG)


-- In June we had a total count of Temperatures taken of 1700, with an average (mean) of 74.9, falling within the range of 64.0 and 85.0 degrees.

![December Tempertures](https://github.com/Roland791/Surfs_up/blob/main/Images/Dec_Temps.PNG)

-- In December we had a total count of Temperatures taken of 1517, with an average (mean) of 71.0, within the range 0f 56.0 and 83.0 degrees.


-- Standard deviation is 3.25 in June and 3.75 in December, -- making a .5 difference in the two different seasons

##Summary
Based on the temperature data, it appears that the annual weather is rather consistent and in the right range to justify a presence of a surf shop. In addition to that, given the data that we currently have avaialble, by adding precipitation data into the mix through an additional query, we could identify whether there are periods where precipitation could factor into feasibility. Finally, by running a query and grouping by measurement location, you could also narrow down the best locations on the islands to set up shop.

