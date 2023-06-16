FILTER COMMANDS AND PIPELINE
-----------------------------------

1. sort : to sort the content in ascending or descending order

syn: sort <filename>
     sort -r <filename>
     sort -n <filename>

2. uniq : it will display duplicates content.

syn: uniq <filename >  : it will remove duplicates one and print that data only one time.

syn:  uniq -c filename  : it will display no. of occurance.
syn: uniq -d filename   : it will display only duplicates one.


3. head  ---> it will display the top 10 lines.

syn: head filename
 syn: head -n filename
   n = nos. of line

4. tail :  it will display 10 lines from the bottom to top.
syn: tail filename
syn: tail -n filename


5.cut : for selecting a specific column of a file.

syn: cut -b2 filename

6. find : used to find a particular file whithin a dir.
syn:  find <filename>

7. grep : (global regular expression print) :

it filter the content of a file which make our search easy.

syn: grep <searchword> filename

8. sed : stream editor 

syn: sed 's/old-content/new-content/' filename
     sed 's/old-content/new/g' filename

pipeline
------------

ex:  cat filename | head -4 | tail -2


tr : translate

cat filename | tr a A 

