# Comma to Colon

A Python 3 script to convert a CSV file to a folder of Kirby CMS content files.

Originally built to migrate pages from A N Other CMS into Kirby CMS content .txt files. It's not perfect but it does simplyfy things.

### How it works

+ The first row of the CSV file is taken to be a header row for the columns. One of these headers must be 'title' (lower case) but the rest can be anythign you like.
+ The script will create YAML files using the cells in the header row to create the categories (ie the CSV header metadesc would become metadesk: in the YAML file.