Tiny Search
-----------

How many lines of code it takes to write a good, understandable, full-text search engine?

For now, this repository has two Scala versions of the Vector Space Model. They are almost the same code, except that one of them ("freakinTinySearch.scala") don't try to be understandable nor that extensible.

Warnings:

-   This is not intented for real world production code
-   The Scala code calculates document norm and term IDF on-the-fly while processing the query. This is far from optimal, but it makes things shorter.
    
    