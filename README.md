# ACID-Compliant Multi-Tenant Library Resource Engine

<img width="2880" height="2160" alt="image" src="https://github.com/user-attachments/assets/f487dde2-9cfe-4608-9ad8-cd38ce45f67d" />


A comprehensive web-based Library Management System (LMS) developed to digitize and streamline library operations, including book cataloguing, borrowing, and return processes. This project was completed as a Complex Engineering Problem (CEP) for the Database Management Systems course at Mehran University of Engineering and Technology.

## Project Overview
The LMS project addresses challenges in modern libraries such as book management, user engagement, and resource accessibility by leveraging technology to improve overall efficiency. The system provides tailored features for different stakeholders, including librarians and students.

## Key Features
- **Book Management**: Allows librarians to add new books to the library collection, update existing book records, and remove books that are no longer in circulation.
- **Borrower Management**: Enables librarians to register new borrowers, update borrower information, and keep track of borrower transactions such as book loans and returns.
- **Transaction Management**: Facilitates the borrowing and returning of books by borrowers, maintains transaction records, and updates book availability based on borrower actions.
- **Genre and Publisher Management**: Provides options to categorize books by genre and publisher, allowing for easier browsing and organization of library collections.
- **Search and Filtering**: Allows users to search for books based on various criteria such as title, author, genre, publisher, and more, enhancing discoverability and accessibility of library resources.
- **User Interface**: Offers a user-friendly interface for librarians and library staff to perform administrative tasks, manage library operations, and generate reports as needed.

## Benefits

- **Efficiency**: Streamlines library operations, reduces manual tasks, and improves overall efficiency in managing library resources and transactions.
- **Organization**: Provides a systematic approach to cataloging books, tracking borrower activity, and maintaining library records, leading to better organization and management of library collections.
- **Accessibility**: Enhances accessibility to library resources by enabling users to easily search for and find books based on their preferences and interests.
- **Data Insights**: Offers valuable insights into library usage patterns, book popularity, and borrower behavior through data analytics and reporting features, aiding in informed decision-making and resource allocation.

## Technologies Used
* **Frontend**: [Streamlit](https://streamlit.io/) (for building the interactive web interface).
* **Backend**: Python (logic and database connectivity).
* **Database**: MySQL (relational database management).
* **Development Tools**: PyCharm IDE, Visual Paradigm (for ER modeling).

## Database Schema (ER Model)

<img width="928" height="508" alt="image" src="https://github.com/user-attachments/assets/fd421336-d3ca-4be3-bc73-39b1891ce303" />


The system utilizes a relational model connecting entities including **Books**, **Genres**, **Publishers**, **Borrowers**, and **Transactions**. Foreign key constraints ensure referential integrity across all tables.

## Documentation
For a detailed breakdown of the system architecture, ER diagrams, and implementation logic, please refer to the project report:

[**View Project Report [PDF]**](https://github.com/mashaalzulfikar/Library-Management-System-Using-Python-and-MySQL-Workbench/raw/main/21CS041,%2021CS077,%2021CS105%20DBMS%20CEP.pdf)

*(Note: If the preview fails due to file size, please download the file to view it.)*
