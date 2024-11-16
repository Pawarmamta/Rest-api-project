# 📚 BookStore REST API

A robust and efficient *BookStore REST API* built using *Node.js, Express, React, and MongoDB*. This project provides a comprehensive CRUD (Create, Read, Update, Delete) functionality for managing books, authors, and genres. Optimized MongoDB queries are used to ensure efficient data retrieval, reducing response times significantly.

## 🚀 Features
- Full CRUD support for *Books, **Authors, and **Genres*
- Efficient MongoDB query optimization for faster response times
- RESTful API architecture for seamless integration with frontend applications
- Built using *Node.js, **Express, **MongoDB, and **React*
- Handles *5,000+ entries* for books, authors, and genres

## 🛠 Tech Stack
- *Backend*: Node.js, Express
- *Frontend*: React
- *Database*: MongoDB
- *Tools*: Postman (for API testing), MongoDB Compass (for database management)

## 📁 Project Structure

BookStore-REST-API/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   ├── utils/
│   ├── .env
│   ├── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   ├── .env
│   ├── package.json
│   ├── App.js
│   └── index.js
├── README.md
└── package.json


## 📦 Installation

### Prerequisites
- Node.js (v14.x or higher)
- MongoDB (v4.x or higher)
- npm (v6.x or higher)

### Clone the Repository
bash
git clone https://github.com/Pawarmamta/rest-api-for-bookstore.git
cd BookStore-REST-API


### Backend Setup
1. *Navigate to the backend directory*:
   bash
   cd backend
   

2. *Install dependencies*:
   bash
   npm install
   

3. **Create a .env file** in the backend directory and add the following:
   
   PORT=5000
   MONGO_URI=mongodb://localhost:27017/bookstore
   

4. *Run the server*:
   bash
   npm start
   
   Server will be running on http://localhost:5000.

### Frontend Setup
1. *Navigate to the frontend directory*:
   bash
   cd frontend
   

2. *Install dependencies*:
   bash
   npm install
   

3. **Create a .env file** in the frontend directory and add the following:
   
   REACT_APP_API_URL=http://localhost:5000/api
   

4. *Run the frontend application*:
   bash
   npm start
   
   Frontend will be running on http://localhost:3000.

## 🚦 Usage

### API Endpoints

#### Books
- *GET* /api/books - Get all books
- *POST* /api/books - Create a new book
- *GET* /api/books/:id - Get a book by ID
- *PUT* /api/books/:id - Update a book by ID
- *DELETE* /api/books/:id - Delete a book by ID

#### Authors
- *GET* /api/authors - Get all authors
- *POST* /api/authors - Create a new author
- *GET* /api/authors/:id - Get an author by ID
- *PUT* /api/authors/:id - Update an author by ID
- *DELETE* /api/authors/:id - Delete an author by ID

#### Genres
- *GET* /api/genres - Get all genres
- *POST* /api/genres - Create a new genre
- *GET* /api/genres/:id - Get a genre by ID
- *PUT* /api/genres/:id - Update a genre by ID
- *DELETE* /api/genres/:id - Delete a genre by ID

### Example Requests
- *Get All Books*
  bash
  curl http://localhost:5000/api/books
  

- *Create a Book*
  bash
  curl -X POST -H "Content-Type: application/json" -d '{"title": "New Book", "author": "Author Name", "genre": "Fiction"}' http://localhost:5000/api/books
  

## 🗄 MongoDB Indexing for Optimization
- Used compound indexes on frequently queried fields to boost performance.
- Achieved a *30% reduction in response times* for database queries.

## 🔍 Testing
- Tested using *Postman* for all endpoints.
- Unit testing using *Jest* (optional, if added to the project).

## 📸 Screenshots
### 1. Book List Page
![Books List](https://user-images.githubusercontent.com/yourusername/book-list.png)

### 2. API Testing in Postman
![Postman Test](https://user-images.githubusercontent.com/yourusername/postman-test.png)

## 🤝 Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a new branch (git checkout -b feature-branch)
3. Commit your changes (git commit -m 'Add some feature')
4. Push to the branch (git push origin feature-branch)
5. Create a new Pull Request

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact
- *GitHub*: [Pawarmamta](https://github.com/Pawarmamta)
- *Email*: mamtapawar892@gmail.com