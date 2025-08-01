# Issues and treatments
| Feature | Issue | Treatment | Treatment applied |
| - | - | - | - |
|**Entire crossing**||||
||periods at end of string|Bulk remove|✔️|
||periods sandwiched between words|Bulk replace with space|✔️|
||inconsistent indicators for crossroads (i.e. "&", "AND", "/")|Bulk replace with "/"|✔️|
||Address inputted more than once|Manual edit|✔️|
||Word "OF" included after "BLOCK"|Bulk remove|✔️|
||Consecutive whitespaces|Bulk eplace with single whitespace|✔️|
||Only street name is included and street crosses multiple zip codes|See [notes](#notes)¹||
|**Zip codes**|  |  |  |
||Zip code is mangled such that it has too many or too few characters (e.g. "908145" instead of "90814")|Manual edit|❌|
||Zip code is mangled such that it has too many or too few characters and is very ambiguous (e.g. "9080" instead of "90805" or "90807")|Manual edit|❌|
||Zip code is missing|See [notes](#notes)¹|❌|
|**Address/block number**|  |  |  |
||"TH" appended to block number (e.g. "1200TH BLOCK")|Bulk remove|❌|
||Letter inserted into address or block number (e.g. "13P00 BLOCK E 17TH")|Manual edit|❌|
|**Block indicators**||||
||"BLOCK" abbreviated or mangled to "BLK\|BLOK\|BL\|BKL\|BLOC"|Bulk edit|❌|
|**Street names**||||
||Inconsistent abbreviation for "Street", "Road", "Avenue"|Bulk edit|❌|
||Inconsistent abbreviation/input for "Pacific Coast Highway"|Bulk edit|❌|
||Inconsistent input for "Long Beach Blvd"|Bulk edit|❌|
|**City names**||||
||Inconsistent input for "Long Beach"|Bulk edit|❌|
||City name is missing|See [notes](#notes)¹|❌|
|**State name**||||
||State name is missing|See [notes](#notes)¹|❌|

# Notes
¹ For the moment, the issue with missing data will go unresolved. Addressing this has slowed down progress greatly and requires resources that are not available to me. It will be tabled for a later date, when a ready solution is available.
