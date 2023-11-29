## Pull article-IDs for all relevant library items
For example, find views and downloads for all Scientific Reports published in 2022.
* In the Admin account, go to _Batch Management_ in top-right. Choose _Public_ items and then select Scientific Reports under content types. 
* Open up and filter by publication year in Power Query Editor following the steps [described here](https://github.com/ffionbell/ices-library/wiki/How-to-pull-all-publications-for-a-year-out-of-ICES-library). Keep the article-ID, title, DOI columns (and anything else relevant: EG, SG, etc).

## Interact with figshare API to pull the views and downloads per article-ID
* Go to this google sheet [API-views-downloads-query](https://icesit.sharepoint.com/:u:/s/icesintranet/publications/Ecgg3KHew0VFsT3MON38TzUBAWgxdoU026auyI1q6RG8yw?e=Ny4YHG) (in Publications intranet document library).
* Past the article-IDs in column A.
* Check the query in column B: https://stats.figshare.com/total/**downloads**/article/ or https://stats.figshare.com/total/**views**/article/
* Column C should automatically populate - it may take a while to think if there are many article-IDs but it'll get there in the end.

![image](https://github.com/ffionbell/ices-library/assets/79839504/7d3c2fae-19d8-4e0a-9e20-e0a06666a786)

