# Comma to Colon

A Python 3 script to convert a CSV file to a folder of Kirby CMS content files.

If you're moving from A N Other CMS to Kirby you've probably got to transfer the pages and blog posts from the older system. Assuming these are stored in an SQL file you can export them as CSV and run that file (after a bit of tidying up) through this script to generate a folder full of Kirby .txt content files.

### How it works

+ Run the Python script.
+ Select the CSV file you wish to convert.
+ Input the .yml file name you wish to use. Each row of the csv will be turned into a name.txt file in its own folder.
+ Select where you want to save the created files and folders.
+ The first row of the CSV file is taken to be a header row for the columns. One of these headers must be 'title' (lower case) but the rest can be anythign you like.
+ The script will create YAML files using the cells in the header row to create the categories (ie the CSV header metadesc would become metadesc: in the YAML file.

### Kirby licences

Try Kirby for free: https://getkirby.com/ then buy a licence when you realise just how great a CMS it is.

If you feel like buying me a beer for writing the script tip me here: https://www.paypal.me/mylesw42
