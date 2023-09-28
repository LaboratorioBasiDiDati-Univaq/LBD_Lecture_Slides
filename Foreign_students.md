## Useful Textbooks and Online Resources for Foreign Students

> Since Laboratorio di Basi di Dati is a second year course in the bachelor degree in Computer Science, it is taught in Italian and all the teaching material is in Italian. However, sometimes there are some foreign students attending the lectures. For these students, I list below some textbooks and online resources useful to integrate or replace the official course textbooks and slides.

- (A) **Database Systems - Concepts, Languages and Architectures**, by Paolo Atzeni, Stefano Ceri, Stefano Paraboschi and Riccardo Torlone.   
      ***Book website***: http://dbbook.dia.uniroma3.it/   
      ***Book PDF***: http://dbbook.dia.uniroma3.it/dbbook.pdf   
  *This book, published by McGraw Hill, is out of print; authors decided to make it available in PDF format at no cost. Slides and exercises can be found on the same book website.*

- (U) **Database Systems: The Complete Book**, by Hector Garcia-Molina, Jeff Ullman, and Jennifer Widom.   
      ***Book website***: http://infolab.stanford.edu/~ullman/dscb.html   
      ***Book PDF*:** there are several free PDF versions of this book available on the internet, just search for them.   
      *Slides based on the book are also available on the book website.*

The following list explains which sections to study in each book, and the corresponding course arguments. In the list, an A prefixes the Atzeni's book references and a U the Ullman's ones. As indicated, many arguments are available on both books, but in some cases there are arguments which are treated, or are better explained, only on one of the books. You should try to integrate such contents.

- **Requirement analysis**: A6.1

- **Conceptual design**: A6.2-A6.6

- **Entity-Relationship diagrams**: A5.1-A5.3 OR U4.1, U4.3, U4.4. 
     *Some concepts are better detailed in U, please try to read both.*

- **Logical design**: A7.1-A7.4, U4.5, U4.6.   
     *Requires the knowledge of the relational model, which is taught in the data bases module and only recalled in the lab module. However, you can read A2.1 or U2.1.3, U2.2.1-U2.2.3 for an introduction.*

- **SQL**: A4.1-A4.6 (*DDL*, *DML*, *QL*,), A12.1 (*Triggers*), U6 (*DDL*, *DML*, *QL*, *Transactions*), U7 (*Triggers*), U8 (*Views*, *Indexes*).   
     *U contains more arguments than A, you should integrate the two books or study all the arguments on U. Moreover, since MySQL is our reference DBMS and its SQL dialect contains some differences with respect to the standard, you should also look at the MySQL manual (https://dev.mysql.com/doc/refman/8.0/en/), in particular, at Chapter 13 (for SQL statement syntax) and Chapter 25 (For stored programs and views).*

- **Database programming**: U9.4 (*Stored procedures*), U9.6 (*Java*), U9.7 (*PHP*).   
     *The Java and PHP programming techniques illustrated in these books are not completely updated with the current technologies. For PHP programming, read the latest documentation about the MYSQLi extension (http://php.net/manual/en/book.mysqli.php). For Java (JDBC) programming, see the Connector/J documentation on the MySQL website (https://dev.mysql.com/doc/connector-j/8.0/en), in particular the installation (4), examples (5), and concepts (7) sections.*
