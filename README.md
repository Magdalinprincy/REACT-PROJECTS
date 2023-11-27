## CRUD Operations and User Roles

### CRUD Operations

The system supports the following CRUD (Create, Read, Update, Delete) operations:

#### Signup & Login

Users can sign up for an account and log in to access the system.

#### Add a New Book to the Library

Only admin members have the privilege to add new books to the library.

#### Add a New Patron to the Library

Admin members can add new patrons to the library.

#### Retrieve Information about a Specific Book or Patron

Users can retrieve detailed information about a specific book or patron.

#### Update the Details of an Existing Book or Patron

Admin members can update the details of existing books or patrons.

#### Delete a Book or Patron from the System

Admin members can delete books or patrons from the system.

### User Roles

The system has two types of user roles:

#### Admin/Staff

Admins members are responsible for managing the library's operations. They have the following privileges:

- Add new books to the library.
- Update the details of existing books.
- Delete books from the library's collection.

#### Regular Users

Regular users can perform the following actions:

- View the available books in the library

**Note: Only admin members have the privilege to add books, while regular users can only view and purchase them.**

## Environment Variables

Before running the application, make sure to set up the following environment variables:

- **ADMIN_USERNAME:** admin

- **ADMIN_PASSWORD:** admin

- **GUEST_USERNAME:** guest

- **GUEST_PASSWORD:** guest
