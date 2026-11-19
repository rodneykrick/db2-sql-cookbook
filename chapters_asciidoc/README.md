# Content 

In this folder we save all chapters of the book. The root-level `book.adoc` master document includes them in reading order. Update that file when adding, removing, or reordering a chapter; the filename numbers are a helpful convention, but the include order is authoritative.

Writing conventions:
+ always write the text in English
+ keep it simple and stupid
+ use the Db2 sample database for your examples

If you insert code, tag it as follows:

    [source, sql]  
    ....  
    SELECT ...  
    ....  

If the output of your statements renders as a table, align all the columns to give them a better readability as text, for example:

    |===
    |Column1        |Column2|Column3
    |ValueVeryLong  |Val    |-
    |===
  
If you want a concept, a word to come to the index, just put write it in double parenthesis: 
    
    This is a  ((word)) to index. 

... more to come  
