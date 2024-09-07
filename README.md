# Book Keeper Application

Book Keeper is a CRUD (Create, Read, Update, Delete) application that allows users to manage a collection of books. This project uses various modern web development technologies to deliver a simple and efficient solution for managing book records.

## Features

- **Create**: Add new books to the collection.
- **Read**: View all books in the collection.
- **Update**: Edit details of existing books.
- **Delete**: Remove books from the collection.

## Technologies Used

### Backend
- **Node.js**: A JavaScript runtime built on Chrome's V8 engine, used for server-side development.
- **Express.js**: A minimal and flexible Node.js web application framework that provides a robust set of features for building APIs and web applications.
- **MySQL2**: A MySQL client for Node.js, providing an easy way to connect and interact with the MySQL database.
  
### Database
- **MySQL**: An open-source relational database management system. It is used to store book records, including title, description, price, and cover image.

### Middleware
- **CORS (Cross-Origin Resource Sharing)**: Enabled via the `cors` package to allow secure communication between the backend and any front-end clients, regardless of their origins.

### API
The Book Keeper application provides a RESTful API to interact with the database. The following operations are supported:
- **GET /books**: Retrieve all books.
- **POST /books**: Add a new book.
- **PUT /books/:id**: Update an existing book.
- **DELETE /books/:id**: Delete a book by its ID.

## Project Structure

- **Express Server**: Handles incoming requests and routes them to appropriate handlers for creating, reading, updating, or deleting book entries.
- **MySQL Integration**: Express communicates with the MySQL database to perform CRUD operations.
- **CORS Middleware**: Ensures that the API can be accessed by front-end applications running on different domains.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
