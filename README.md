# Amazon-Data-Dedup-Codes
To deal with the problem of having multiple records getting pulled each time a sync is done through Amazon Ads & MWS connectors from daton, these codes will be helpful in consolidating the latest and accurate data as per the requirements.

The main focus of this package is to transform the raw amazon data tables with multiple records/duplicate entries to Analytics-ready tables based on latest _daton_batch_runtime and _daton_batch_id along with all the other hierarchy of data which is table specific. 

[Please refer to this for more information on Fields, tables for Amazon Ads data.](https://docs.sarasanalytics.com/integrations/data-sources/saas-integrations/amazon-ads). [Try looking at this to understand everything about Amazon MWS data.](https://docs.sarasanalytics.com/integrations/data-sources/ecommerce/amazon-mws)

## Commonly-used-Amazon-MWS-Tables

Below are the commonly used amazon MWS tables, from the set of shared codes, which are analytics-ready. These codes will help you in extracting the Overall sales metrics on different hierarchies of data.

![Amazon MWS Tables Description](https://user-images.githubusercontent.com/69815945/111434713-e0ccf400-8725-11eb-874c-0477dbfd8a1c.png)

## Commonly-used-Amazon-Ads-Tables

Daton has three different Amazon Ads connectors through which we can pull out the Ads data for each AdType Seperately. 
-Sponsored Brands
-Sponsored Display
-Sponsored Products

Below are the tables from each AdType which will be helpful in finding out the insights from Ads Perspective. 











