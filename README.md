Readers — A table that holds information about the readers.
Books — A table that contains information about the books.
Libraries — A table that represents the libraries in the network.
Transactions — A table that stores information about which books are borrowed by readers, when they were taken, and when they should be returned.
The relationships between the tables are as follows:

One reader can borrow multiple books, so there is a one-to-many relationship between Readers and Transactions.
A book can only be borrowed once at a time, so there is a one-to-many relationship between Books and Transactions.
Each book belongs to a specific library, so there is a one-to-many relationship between Libraries and Books.
