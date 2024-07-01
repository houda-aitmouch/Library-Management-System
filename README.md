## Library Management System

 Objective

Create a system for managing library books, allowing students to issue and return books and admins to manage the inventory.

# Admin's Perspective

1. **Login**: Admin logs in with predefined credentials.
2. **Manage Books**:
   - **Add**: Add new books to the inventory, stored in a binary search tree (BST) for sorted order.
   - **Delete**: Remove books from the inventory.
   - **Update**: Modify book names and quantities.
# User's Perspective (Students)

1. **Login**: Students log in with their university ID.
2. **Issue Books**:
   - Search for books by name in the BST.
   - Messages for unavailable books:
     - "Book is not available in the library."
     - "This book is currently unavailable. Please try after some days."
   - Limit: Maximum of 2 books issued simultaneously.
3. **Return Books**: Update inventory upon return.
4. **Records**: Record issuing date and time; apply fines for late returns.
