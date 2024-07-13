# SQL-Basics-Practice
CREATE TABLE Books (
    BookID INTEGER PRIMARY KEY,
    Title TEXT,
    Author TEXT,
    PublicationYear INTEGER,
    Price REAL
);

INSERT INTO Books (Title, Author, PublicationYear, Price) VALUES
('To Kill a Mockingbird', 'Harper Lee', 1960, 12.99),
('1984', 'George Orwell', 1949, 10.99),
('The Great Gatsby', 'F. Scott Fitzgerald', 1925, 11.99),
('Harry Potter and the Sorcerer''s Stone', 'J.K. Rowling', 1997, 14.99),
('The Catcher in the Rye', 'J.D. Salinger', 1951, 9.99);

SELECT * FROM Books;

SELECT * FROM Books WHERE PublicationYear > 2000;

SELECT * FROM Books WHERE Author = 'J.K. Rowling';

UPDATE Books SET Price = 13.99 WHERE Title = 'To Kill a Mockingbird';

DELETE FROM Books WHERE Title = 'The Catcher in the Rye';

This SQLite database assignment provided valuable hands-on experience in working with relational databases. I learned how to create a database, design a table with specific columns and data types, and perform various SQL operations such as INSERT, SELECT, UPDATE, and DELETE. One of the key challenges I faced was setting up the SQLite environment. However, overcoming this challenge helped me better understand the process in order to complete the assignment. I found the process of querying the database particularly interesting, as it demonstrated how powerful SQL can be in extracting specific information from a dataset. This assignment has given me a solid foundation in database management and SQL, skills that I believe will be valuable in future programming and data analysis tasks.
