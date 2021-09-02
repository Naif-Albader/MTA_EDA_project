![IMG_4849](https://user-images.githubusercontent.com/63314269/131738196-70750756-8fd4-4af2-9a66-7571eee3a19f.JPG)


### Advertising campaign for IKEA

### Company info
IKEA is a Swedish company that designs and sells ready-to-assemble furniture, kitchen appliances, and home accessories, among other goods and home services

### Opportunity  
IKEA did an Advertising campaign in Paris and it was a sleeping capsule connected to a bike, you can take a nap in the capsule or you get the chance to try their bed. So I found an opportunity to do the same advertising campaign in NYC based on MTA data to know which stations are most likely to get us noticed so that we can distribute our capsules to those stations.

### Value added to the company?
* Getting peoples attention to our product
* Increasing sales

#### Question/need:
* What are the top stations on traffic to do the campaign on those stations?
* Is weekday or weekend better to do the campaign on?
* What is the best time of the day to do the campaign?

#### Data Description:
the MTA dataset represents the number of ENTRIES and EXITS of the stations in New York City,

I will do the analysis on the latest 3 months period provided by the mta.info website which is June to Sep of 2021. 
* The campaign will start as soon as possible so we want to know the current behavior of MTA data


#### Dataset Description:

| Field Name | Description                                                                     |
|------------|---------------------------------------------------------------------------------|
| C/A        | Control Area (A002)                                                             |
| UNIT       | Remote Unit for a station (R051)                                                |
| SCP        | Subunit Channel Position represents an specific address for a device (02-00-00) |
| STATION    | Represents the station name the device is located at                            |
| LINENAME   | Represents all train lines that can be boarded at this station                  |
| DIVISION   | Represents the Line originally the station belonged to BMT, IRT, or IND         |
| DATE       | Represents the date (MM-DD-YY)                                                  |
| TIME       | Represents the time (hh:mm:ss) for a scheduled audit event                      |
| DESC       | Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours)   |
| ENTRIES    | The comulative entry register value for a device                                |
| EXITS      | The cumulative exit register value for a device                                 |



#### Tools:
* Technologies: SQL, SQLite ,Python, Jupyter notebook
* Libraries: Numpy, Pandas, Matplotlib, Seaborn


