# Blogger

A full-stack blogging platform built with Node.js, Express, MongoDB, and EJS.

## Features

- 👤 User authentication (signup, signin, logout)
- 📝 Create, read, and comment on blog posts
- 🖼️ Image upload support for blog covers
- 📱 Responsive Bootstrap design

## Tech Stack

- Backend: Node.js, Express
- Database: MongoDB
- View Engine: EJS
- Authentication: JWT
- File Upload: Multer

## Quick Start

1. **Clone and Install**
```bash
git clone https://github.com/pawan-r4ju/Blogger.git
cd Blogger
npm install
```


2. **Environment Setup Create .env file:**
```bash
PORT=8000
MONGO_URL=mongodb://0.0.0.0/blogs
```
3. **Start Server:**
```bash
npm run dev
```
Visit http://localhost:8000 in your browser.

## Project Structure:
```bash
├── middlewares/        # Auth middleware
├── models/            # Database models
├── public/           # Static files
├── routes/           # API routes
├── services/         # Business logic
├── views/            # EJS templates
└── app.js           # Entry point
```
## API Routes

- `POST /user/signup`: Create a new user account.  
- `POST /user/signin`: Login and authenticate a user.  
- `GET /blog/add-new`: Create a new blog post.  
- `GET /blog/:id`: View a specific blog post by ID.  
- `POST /blog/:id/comment`: Add a comment to a specific blog post.

## Dependencies

- `express`: ^4.18.0  
- `mongoose`: ^6.3.0  
- `ejs`: ^3.1.0  
- `jsonwebtoken`: ^8.5.1  
- `multer`: ^1.4.4  
- `dotenv`: ^16.0.0  
- `cookie-parser`: ^1.4.6  

## Contributing

- Fork the repository.  
- Create a feature branch.  
- Commit your changes.  
- Push to the branch.  
- Create a pull request.

## License

- MIT  

## Author

- **Pawan Raju**  

## Made with ❤️ and JavaScript.

