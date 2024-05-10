# LibraryManagementSystem Android Application using Java and SQLite



This Android application serves as a comprehensive Library Management System, offering various functionalities to efficiently manage library operations. Users can easily add new books, publishers, branches, members, and book loans to the library database. 

The application allows users to add new books by specifying details such as book ID, title, publisher name, author name, branch ID, and access number. Publishers can be added by providing the name, address, and phone number. Similarly, users can add new branches by entering the branch ID, branch name, and address. Additionally, members can be added to the system with details including member ID, name, address, phone number, and any unpaid dues.

One of the key features of this application is the ability to give book loans to library members. Users can specify the access number, branch ID, member ID, date out, and due date to complete the loan process. 

The application also provides a search functionality, allowing users to search for books by their ID. Upon searching, the application displays book details such as book ID, title, and publisher name. 

Behind the scenes, the application uses an SQLite database to efficiently store and manage all library data. The database consists of tables for Book, Publisher, Branch, Member, Book_Author, Book_Copy, and Book_Loan, ensuring a well-organized and structured data management system.

To enhance user experience, the application includes error handling features to ensure data integrity and proper functioning. It provides error messages for incomplete form submissions and failed database operations, ensuring a smooth user experience.

In summary, this Library Management System Android application offers a user-friendly interface, robust database management, error handling features, and various functionalities to simplify the process of library management and enhance user experience.
