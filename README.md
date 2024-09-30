# wikidata-nz-authority-spread
Wikidata exports of New Zealand authority control information.

This query is an attempt to expose wikidata person metadata about New Zealand people as a spreadsheet rather than as triples, to allow those with spreadsheet skills insights into the data extractable from wikidata.

# The Data #
There are literally billions of itmes and tens of thousands of possible properties in wikiadata. I have chosen to select those items which are marked as people and either citizens or residents of New Zealand. Each item is a single row in the spreadsheets. The first column is the wikidata iternal identifer for this person. The next three are built-in textual shortcuts to identify the person (librarians familiar with authority control will be rightly horrified at lack of normalisation in these fields). Every other column is a a New Zealand-related, public-web-exposed identifier for that person. 

# Notes #
* This is strictly an extract, there is no way to use these spreadsheets to upload changes to wikidata. It may be possble to find use these spreadsheets to find issues that can be fixed via other wikidata editing channels.
* This extract contains information on living people, but is extracted from a public source. If there is a problem with any of the data, fix it on wikidata.org and ping my to update the spreadsheets and flush the old data.load
* the data contains unicode characters. The CSV will need to be loaded as UTF-8.
* If you're aware of any New Zealand-related wikidata identifiers, let me know.
* Many people are missing various of their identifiers, feel free to fix these on wikidata.org
* I'm still looking for a good definition of New Zealander, let me know if you have any ideas.
