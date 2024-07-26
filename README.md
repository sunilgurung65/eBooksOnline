E-Commerece Project (eBooksOnline)

Student Name: Sunil Gurung
Student Id: 8965476
Date: 2024/07/25

Technology Stack
Frontend: ReactJS
Backend: Node.js
Database: MongoDB (Atlas)

Project Setup
1. Project Initialization: Created a new repository on GitHub and named as "eBooksOnline" and cloned to local machine.\
2. Frontend Setup: ReactJS for creating the front-end part.
3. Backend Setup: Node.js with express for backend part.
4. Database: MongoDB(Atlas)

Database Design Schema

Admin Schema (MongoDB)
1. userName: String
2. password: String

User Schema (MongoDB)
1. fullName: String
2. email: String
3. contact: String
4. address: String

Category Schema (MongoDB)
1. category: String

Books Schema (MongoDB)
1. bookName: String
2. price: Number
3. stock: Number
4. authorName: String
5. imageUrl: String

Cart Schema (MongoDB)
1. bookName: String
2. price: String
3. quantity: String
4. imageURL: String

checkOut Schema (MongoDB)
1. bookName: String
2. price: String
3. quantity: String
4. imageURL: String
5. fullName: String
6. email: String
7. contact: String
8. address: String
9. totalAmount: Number
10. methodOfPayment: String
