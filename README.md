# Note Keeping Application
This project is a simple Note Keeping Application built with Node.js, Express.js, and MongoDB. It provides a RESTful API that allows users to create, read, update, and delete notes efficiently. Each note consists of a title, content, and a creation date. The API also supports searching notes by title or content and includes pagination for retrieving notes in manageable sets.

## Features
- **CRUD Operations**: Users can create, retrieve, update, and delete notes.
- **MongoDB Integration**: Utilizes Mongoose for object modeling and database interactions.
- **Error Handling**: Gracefully handles errors, returning appropriate status codes and descriptive messages.
- **Search Functionality**: Search for notes by title or content using a query parameter.
- **Pagination**: Paginate the notes list, allowing users to view a limited number of notes at a time and navigate through pages.

## API Endpoints
- **GET /notes**: Retrieve all notes (supports pagination).
- **POST /notes**: Add a new note.
- **DELETE /notes/:id**: Delete a specific note by its ID.
- **PUT /notes/:id**: Update a specific note by its ID.
- **GET /notes/search?query=YOUR_QUERY**: Search notes by title or content.

## Technologies Used
- **Node.js**
- **Express.js**
- **MongoDB**
- **Mongoose**
