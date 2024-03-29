# db2-sql-cookbook
Colaboration platform for the new version of the old Db2 SQL Cookbook.

PDF Version can be found here: http://db2-sql-cookbook.org/pdf/Db2_SQL_Cookbook.pdf

[Preamble]
== Introduction

I started using Db2 in 1991. Five years later,  Graeme Birchall released the first version of his "Db2 SQL Cookbook". This book helped me to learn SQL and I used it a lot of times to learn new stuff and to check how he writes similar queries (the first time I can remember was when I took my first Db2 Certification. "IBM Certified Solutions Expert -- DB2 UDB V5 Application Development", in October 2000 at IDUG in Geneva). The last version of the book I am aware of was published in 16 August 2011, based on version 9.7 of Db2 LUW. In the past years I've googled sometimes to check if there was a new version of the book and if someone decided to maintain it. I didn't find any new version and, as far as I know, Graeme Birchall deleted everything he had (his homepage, where the book was published and every links that he maintained). 

Because I've learned a lot and I found the book very good to help people that are starting with SQL, I decided to take the contents of the book as they were in the last published version and use it to initiate a new version of the book. The idea behind it is to show how SQL works and enrich it with examples of the daily work with SQL. I use SQL almost everyday in my work. As I've heard in one of the many conferences I've visited in the last 30 years, "SQL is a very easy language, when you formulate very easy queries". You will find easy queries for simple use cases and complex queries for complex use cases. This is not necessarily a rule: I've seen many complex queries for simple use cases and great simple queries for complex use cases. The best SQL statements follow the old good KISS rule: Keep It Simple and Stupid.

Somethings that I decided to change in this book, comparing to the original version:

* I've migrated the text to asciidoc and opened a project in GitHub (https://github.com/rodneykrick/db2-sql-cookbook). As the people at *_Asciidoc_* use to say: "It's just text, mate!" I believe with this format the community will be able to contribute and improve the content.  
* Graeme tried to keep syntax diagrams in his book. I'll try to follow a more practical approach in this version of the book. You won't find syntax diagrams, just sample code that was tested in Db2 (some will work in other RDBMS, it would be great and helpful if we manage to check and document this). If you want to learn more about the statement and the syntax, you should use the SQL reference book of your RDBMS, in the version you are using. 
* To publish the result (the last version of the book) I reserved a new domain (http://db2-sql-cookbook.org). I'll try to generate a HTML Version of the book and upload it as frequently as possible. The PDF version can be found here: http://db2-sql-cookbook.org/pdf/Db2_SQL_Cookbook.pdf. It will be generated together with the HTML version.

Some notes: 

* I will manage the project in the first phase. I hope, the experts outside will join it, enrich and update the content (this is what I also intend to do). Maybe we get more and more people involved and keep this book up to date. 
* If someone knows Graeme Birchall please let him know that we are trying to keep his work going on. I only decided to "clone" his book because of his statements regarding the distribution of the book (see <<why.free>>). I really searched for him in the www, but wasn't successful. As I finished the first version I've put a message on the Db2 Listserver (hosted at http://www.idug.org) and got an answer from Ian Bjorhovde. He had the same idea in the past and contacted Graeme. Graeme gave him a copy of his book and wrote in his answer: "So think of this as one of those copyleft situations where I am putting the document in the public domain". Andres Gomez Casanova suggested to put the work under the Creative Commons Attribution-ShareAlike 4.0 International license with the following arguments: "With a specific license the original work from Graeme and any improvement will remain with the same rights, and prevent from any unfair use". I think this is a good thing!   
* And just another point: if you never worked with SQL, I recommend you to start with the SQL Tutorial in w3schools. It is a great site to start learing it! [https://www.w3schools.com/sql/default.asp]

Have fun! 

Rodney Krick + 
rk@aformatik.de
