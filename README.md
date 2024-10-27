
---

# GraphQL Client for Marvel Authors and Books

## Description
This project is a front-end application built with React or Next.js that uses Apollo Client to interact with a GraphQL server. It provides CRUD functionality for managing a collection of authors and books, as well as search functionality for genre, price range, and author name. The application features modal forms for adding/editing records and a responsive UI with Material-UI components.

## Features
- **Authors Page**: Displays a list of authors with details including name and number of books. Allows for editing and deleting authors, and includes an "Add Author" button with a modal form for adding new authors. Each author name links to a details page.
- **Author Details Page**: Shows detailed information about a single author, including a list of books (up to 3). Includes options to edit or delete the author.
- **Books Page**: Displays a list of books with title, genre, and price. Allows for editing and deleting books, and includes an "Add Book" button with a modal form for adding new books. Each book title links to a details page.
- **Book Details Page**: Shows detailed information about a specific book, including the author’s name. Also includes options to edit or delete the book.
- **Search Page**: Allows users to search by genre, price range, or author name. Search inputs dynamically change based on the selected query type (e.g., genre, price range, or name).
- **Navigation**: Includes a navbar for seamless navigation throughout the application.

## Tech Stack
- React or Next.js
- Apollo Client
- GraphQL
- Material-UI

## API Endpoints (GraphQL)
1. **getAuthors**: Retrieves a list of authors with fields for name and number of books.
2. **getBooks**: Retrieves a list of books with fields for title, genre, and price.
3. **addAuthor/editAuthor/deleteAuthor**: Manages authors.
4. **addBook/editBook/deleteBook**: Manages books.
5. **getAuthorById**: Retrieves details of a specific author, including their books.
6. **getBookById**: Retrieves details of a specific book.
7. **booksByGenre/booksByPriceRange/searchAuthorsByName**: Allows for specific search queries.

## Routes
- **`/`**: Homepage.
- **`/authors`**: List of authors with options to add, edit, and delete.
- **`/authors/:id`**: Details of a specific author.
- **`/books`**: List of books with options to add, edit, and delete.
- **`/books/:id`**: Details of a specific book.
- **`/search`**: Search page for filtering authors and books by genre, price, or name.

## Installation
1. Clone the repository.
   ```bash
   git clone https://github.com/sachindevangan/-GraphQL-Client-for-Marvel-Authors-and-Books
   ```
2. Navigate to the project directory.
   ```bash
   cd graphql-client
   ```
3. Install dependencies.
   ```bash
   npm install
   ```
4. Start the development server.
   ```bash
   npm run dev
   ```

## Usage
- Navigate through authors, books, and search options to manage and explore collections.
- Use the modals to add or edit authors and books.

## License
This project is licensed under the MIT License.

---