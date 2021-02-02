# Online Library Management software 

We want to make a complete Online Library solution that offers the standard functions of a library, namely searching for a book, borrowing a book, returning a book ...

In fact there are three profiles of people who can use this
Online Library:
- Student
- Librarian
- Administrator

Role of the Student:
- Register in the system by providing last name, first name, student card number, email and other info ...
- Change your password and profile 
- Authenticate in the system 
- Find a book with these references
- Display the list of books available by topic 
- Borrow a book starting from its reference
- Etc ....

Role of the Librarian
- Make a complete inventory of all books
- Mark a book as rendered
- Add books-Remove Books
- Show if a book is available or borrowing
- View the list of all overdue books 
- Send a message to all late arrivals (maximum borrowing period is 10 days)
- Etc ....

Role of the administrator
- Remove a student from the system
- Create and edit the Librarian profile


Requirements
------------

  * PHP 7.1 or higher;
  * PDO-SQLite PHP extension enabled;
  * and the [usual Symfony application requirements][2].

Installation
------------

### Step 1 : Clone the project

Now clone the project from github.

```bash
$ git clone https://github.com/er5bus/online-library-management.git
```

### Step 2 : Install dependencies

Now that the project is cloned, running the following command should install all the symfony dependencies:

```bash
$ composer install
```

### Step 3 : Configuration

Now configure the .env file under the root project.

```bash
$ cp .env.example .env
```

### Step 4 : Run the project

Now run this command to run the built-in web server and access the application in your browser at <http://localhost:8000>:

```bash
$ php bin/console server:run
```

That's it.
