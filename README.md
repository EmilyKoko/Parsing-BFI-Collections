# Parsing-BFI-Collections
A programming experiment that uses Python in an attempt to consolidate and structure data from the British Film Institute's online collections database.

The original goal of this project was to write a functional python tool to webscrape the British Film Institute's online collections database and structure that data into an ordered JSON file. The BFI database can be found here: https://collections-search.bfi.org.uk/web. Issues with the responsiveness of the database and difficulties with the web scraper forced me to switch gears.

The resulting final code has created a structured dataset from HTML source files (included in the repo with the title, "BFI_collection_search_results_#") that were manually downloaded from the BFI database. The search terms used in the BFI database to produce the source files were: Search in Film and Television Works > Filter - BFI Filmography >  BFI Filmography - all Works > Date - to 1940. Only 4 of the 14 total pages of results are included in this repo and parsed in the code.

The file "failed_webscrape_bficollections" contains the failed web scraper, with comments regarding the issues I encountered. The file "final_HTMLparsedata_bficollections" is the functional code, from which the dataset was generated as a JSON file titled "output_bfi_early_collection"
