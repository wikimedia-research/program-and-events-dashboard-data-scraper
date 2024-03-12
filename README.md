# This scraper will read the lab_outcomes.csv file and loop through each unique slug and append that slug to the base url on the outreachdashboard. 
# This will download the overview spreadsheet of each campaign/event. The directory containing lab_outcomes sheet should be specified and an output folder should also be specified.
# An origincal copy wil be stored as .csv in the output directory and another copy with some additional columns added for processing purposes will be saved as .xlsx file.  The files are named after their respective slug.
# A list of failed retrievals is also generated of a spreadsheet with a matching slug title was not found on the outreach dashboard. Generally this is due to a mismatch with the name of the event/campaign in the pulled data vs. the name on the outreach dashboard.
# The files are then uploaded to the google drive and the shareable link to the file is writen into the spreadsheet.

