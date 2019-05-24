# Scraping Special Codes for Olympics

Utilizing `read_html` from Pandas to scrape tabular data on Special codes for Olympics. I have used the resulting DataFrame to scrape the table on wikipedia.

## Steps

* Use Panda's `read_html` to parse the URL.

* Find the special codes for the nation/team and assign it to `df`.

* Assign the columns `['Code', 'Nation/Team', 'Years', 'Notes']`

* Drop the `Notes` column from the DataFrame.

* Drop the header row (the first row) and set the index to the `Code` column.

* Loop through the list of codes and print the codes with the Nation/Team.

* Use the DataFrame to perform the lookup.

- - -


