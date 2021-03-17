# Amazon-Data-Dedup-Codes
To deal with the problem of having multiple records getting pulled each time a sync is done through Amazon Ads & MWS connectors from daton, these codes will be helpful in consolidating the latest and accurate data as per the requirements.

The main focus of this package is to transform the raw amazon data tables with multiple records/duplicate entries to Analytics-ready tables based on latest _daton_batch_runtime and _daton_batch_id along with all the other hierarchy of data which is table specific. 

[Please refer to this for more information on Fields, tables for Amazon Ads data.](https://docs.sarasanalytics.com/integrations/data-sources/saas-integrations/amazon-ads). [Try looking at this to understand everything about Amazon MWS data.](https://docs.sarasanalytics.com/integrations/data-sources/ecommerce/amazon-mws)

## Commonly-used-Amazon-MWS-Tables

Below are the commonly used amazon MWS tables, from the set of shared codes, which are analytics-ready. These codes will help you in extracting the Overall sales metrics on different hierarchies of data.

![Screenshot (83)](https://user-images.githubusercontent.com/69815945/111440322-3a382180-872c-11eb-92cf-f20cca8bb754.png)


## Commonly-used-Amazon-Ads-Tables

Daton has three different Amazon Ads connectors through which we can pull out the Ads data for each AdType Seperately. 
1. Sponsored Brands
2. Sponsored Display
3. Sponsored Products

Below are the tables from each AdType which will be helpful in determining the Ads contribution to the overall health of the brand.

![Screenshot (87)](https://user-images.githubusercontent.com/69815945/111442336-4329f280-872e-11eb-87df-17cccd8914ca.png)














