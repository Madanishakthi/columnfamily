# columnfamily
  HBase is a column-oriented non-relational database management system that runs on top of Hadoop Distributed File System (HDFS). HBase provides a fault-tolerant way of storing sparse data sets, which are common in many big data use cases. It is well suited for real-time data processing or random read/write access to large volumes of data.

  Unlike relational database systems, HBase does not support a structured query language like SQL; in fact, HBase isn’t a relational data store at all. HBase applications are written in Java  much like a typical Apache MapReduce application. HBase does support writing applications in Apache Avro, REST and Thrift.

   An HBase system is designed to scale linearly. It comprises a set of standard tables with rows and columns, much like a traditional database. Each table must have an element defined as a primary key, and all access attempts to HBase tables must use this primary key.
In this ticket_booking table there are three columns named pass bio, bus details and staff details info containing three rows basically

![WhatsApp Image 2023-03-18 at 10 04 32 PM](https://user-images.githubusercontent.com/124055684/226121094-f4f3d4b0-5493-4eb9-86c9-eb01ab57e81b.jpeg)

   I deleted the values of row no 01 of mobileno in pass bio.In the second row I inserted the timing in bus details column using put keyword column using put keyword. finally I inserted the last row's updated the salary in staff details using delete keyword.

OPERATION USED:

![WhatsApp Image 2023-03-18 at 10 04 32 PM (1)](https://user-images.githubusercontent.com/124055684/226121131-a249b6c1-3583-4690-8b23-0835940a98de.jpeg)

To make the above operation I used the following keywords:

                        put- put keyword is used to insert and update the values of the paasenger in the table
                        scan- scan keyword is used to display the entities of the table we have created
                        get- get keyword is used to read the values of the table delete- delete keyword is used to delete the value as well as the table

   Pictorial representation of CRUD operation in ticket booking database are attached in the Issues file(3 files) In conclusion, column-family databases are a powerful tool in the world of data management, and their popularity is only expected to grow as organizations continue to generate and collect more and more data.
