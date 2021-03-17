# Amazon-Data-Dedup-Codes
To deal with the problem of having multiple records getting pulled each time a sync is done through Amazon Ads & MWS connectors from daton, these codes will be helpful in consolidating the latest and accurate data as per the requirements.

The main focus of this package is to transform the raw amazon data tables with multiple records/duplicate entries to Analytics-ready tables based on latest _daton_batch_runtime and _daton_batch_id along with all the other fields which are table specific(based on the levels and types of data). 

[Please refer to this for more information on Fields, tables for Amazon Ads data.](https://docs.sarasanalytics.com/integrations/data-sources/saas-integrations/amazon-ads). [Try looking at this to understand everything about Amazon MWS data.](https://docs.sarasanalytics.com/integrations/data-sources/ecommerce/amazon-mws)





