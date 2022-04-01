# Project-Numpy-

Project_data = 'KAG_Conversion_Data.csv'

Data Features:

- ad_id: unique ID for each ad
- xyzcampaignid: an ID associated with each ad campaign of XYZ company
- fbcampaignid: an ID associated with how Facebook tracks each campaign
- age: age of the person to whom the ad is shown
- gender: gender of the person to whom the add is shown
- interest: a code specifying the category to which the person’s interest belongs (interests are as mentioned in the person’s Facebook public profile)
- impressions: the number of times the ad was shown
- clicks: number of clicks on for that ad
- spent: Amount paid by company xyz to Facebook, to show that ad
- total conversion: Total number of people who enquired about the product after seeing the ad
- pproved conversion: Total number of people who bought the product after seeing the ad


The program returns: 

- The total number of unique ad campaigns (xyzcampaignid) does the data contains 
- The number of times each campaign run
- The age groups that were targeted through these ad campaigns
- The average, minimum and maximum amount spent on the ads
- The id of the ad having the maximum number of clicks 
- The number of people that bought the product after seeing the ad with most clicks
- Finds the details of the product having maximum number of purchases
