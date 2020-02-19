# PyBer_Analysis

I've been asked to create an overall snapshot of the ride-sharing data.

Main tools/dependencies: Python, Pandas and Matplotlib

On the master folder, you will find a summary table of key metrics of the ride-sharing data by city type labelled 'summary_data.csv'.
Also, you will find a multiple-line graph that shows the total fare for each week by each city type. This graph is located under the analysis folder labelled as "ChallengePlot.png"

## Key Findings

### Summary table
* 5 key-metrics per city type from the first of January 2019 to eighth of may of 2019 :
  1. Total Rides 
  2. Total Drivers
  3. Total Fares
  4. Average Fare per Ride
  5. Average Fare per Driver

With these key-metrics, I would suggest 3 main things:
1. Urban has the biggest demand for rides, but we have an oversupply. 
2. Due to the high supply in urban areas, the average fare per driver gets affected by more than 3 times compared to the Average Fare per Driver in the Rural Area.
3. Either the company let some drivers loose or it should start a campaign to move some of the Urban drivers to the rural areas until we get the Average Fare per Driver on every city type to almost the same.

### Findings in the Multiple-Line Chart
* Except for the end of April, it looks like the three city types have the same seasonality. It can be appreciated that most of the time, the three cities have a lot of rides or very few rides at the same time (proportionally speaking).
* Just by knowing the total fare we won't be able to appreciate if the demand for the service is growing or not.
* The graph just help us to appreciate when the demand is gonna be higher. Besides the previews points, we are not able to conclude anything else.

### Implication of the data Summarized in the DataFrame and the Multiple-Line chart
* Both data, the summary table and total fare graph, can show us that urban people use a lot the service, thus more drivers and the total fare is bigger. 
* However, I think that both tables are missing data that would have allowed us to make better decisions:
  * Number of rides through time - to see if the demand is increasing or decreasing.
  * Number of drivers through time - to see if the supply is increasing or decreasing.
