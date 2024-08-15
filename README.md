# Rainfall_rescue_scraping

Jupyter Lab tools to scrape the Rainfall Rescue csv data from Ed Hawkins Rainfall Rescue repository. 

Original data located <a href='https://github.com/ed-hawkins/rainfall-rescue'>here - https://github.com/ed-hawkins/rainfall-rescue</a>.

Due to file upload limits long timeseries files can't be provided in GitHub repositories. The example Jupyter lab scripts (paired with the csv files of data location urls) provide examples on how you can open multiple csv data files from the Rainfall Rescue ALLSHEETS repository and work with the precipitation data locally.

In the examples the data is opened with xarray. The coordinate 'site_index' refers to the row in the corresponding csv file for that decade - this way the data can be traced back to the original csv that contains useful information such a site location and calculated totals and errors.

With thank to the <a href='https://www.zooniverse.org/projects/edh/rainfall-rescue'>Rainfall Rescue project and community</a> for thier hard work in making this observational data publically available.
