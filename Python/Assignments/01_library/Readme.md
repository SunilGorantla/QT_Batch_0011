# Class Notes and Assignment

## Assignment - 1: Creation of a College Books Library

### Background
In a college library system, there are multiple copies of various books available for borrowing. Only students with a valid college ID are permitted to check out books. Each student is allowed to have a maximum of five books borrowed at any given time. To borrow more books, a student must first return some of their currently borrowed books to stay within the limit.

### Instructions

#### Step 1: Create the `Student` Class
- This class should have attributes for the student's ID, name, and the number of books borrowed (default should be 0).

#### Step 2: Create the `Book` Class
- This class should have attributes for the book's ID, title, author, year published, and the number of copies left.

#### Step 3: Create the `Library` Class
- This class should store details of students and books.
- It should include functions to add books and student details to the library.
- It should include functions to allow students to borrow books, adhering to the borrowing rules specified.

### Deliverables
Students are expected to implement the classes as described in the instructions and demonstrate the functionality of the system by writing a script that:
- Creates instances of `Book` and `Student`.
- Adds these instances to the `Library`.
- Simulates the process of students borrowing and returning books.
- Ensures that the borrowing rules are followed, and no student exceeds the limit of five borrowed books at a time.

The script should include print statements to show the status of each operation and the current state of the library's books and registered students.

### Submission
Submit your Python script in a `.py` file format along with any notes you have taken during the development process. Ensure your code is well-commented to explain the functionality and logic behind your implementation.
