# example data: duplicate strings (ICD-10 descriptions)

This repo contains data generated from https://www.stata-press.com/data/r18/australia10.dta. ICD-10 codes were used to generate descriptions (strings). 
Strings with 3 or fewer words were selected, and strings containing commas were excluded.

The generating mechanism involved repeated random sampling with replacement to obtain duplicate strings.

1 million records were generated, and the Stata .dta file was split into 100 files, which are made available for download from this repo.

https://www.statalist.org/forums/forum/general-stata-discussion/general/1764113-how-to-count-number-of-distinct-unique-words-in-a-string-variable?p=1764424#post1764424



