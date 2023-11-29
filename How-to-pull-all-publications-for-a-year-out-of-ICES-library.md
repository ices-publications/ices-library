In the Admin account for figshare, go to **Batch Management** in top right.
Under **Download metadata** select _Public_ and _All metadata_. Start metadata download - this might take a while to run. The download csv gets sent to the **editor@ices.dk** inbox

When download arrives, save the csv. Open Excel, go to the _Data tab_ > _Get Data from text/csv_ and import your file. 
Make sure the **File Origin** box at top is set to _65001:Unicode (UTF-8)_ so special characters are brought across. Select _Transform Data_ to open the Power Query Editor window.

Find the column _publication_date_ and filter it by this year.
If you don't want to see external publications, find the _licence_ column and filter out the external publisher licence.

Under _Manage columns_ you can select the columns to keep. Title, doi, publication_date, series, for example. _Close and load_, and the results will show as a table.

## To find the numbers of items published in a year by Series
This can also be found on the ices-library search page. Enter **:publication_date: 2023** in the search bar then check the facets under **Content Type** for numbers.
