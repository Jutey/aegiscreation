# AegisCreation Blog

A modern, full-featured blog platform built with Node.js, Express, and MongoDB.

## Features

- 📝 Create, read, update, and delete blog posts
- 👤 User authentication and authorization
- 💬 Comment system
- 🏷️ Tags and categories
- 🔍 Search functionality
- 📱 Responsive design
- 🎨 Clean, modern UI

## Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose
- **Authentication:** JWT, bcrypt
- **Frontend:** EJS templates, CSS3, JavaScript
- **Other:** dotenv, express-validator

## Installation

1. Clone the repository:
```bash
git clone https://github.com/aegiscreation/blog.git
cd blog
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```env
PORT=3000
MONGODB_URI=mongodb://localhost:27017/aegisblog
JWT_SECRET=your-secret-key-here
NODE_ENV=development
```

4. Start the development server:
```bash
npm run dev
```

5. Open your browser and navigate to `http://localhost:3000`

## Project Structure

```
blog/
├── config/
│   └── db.js
├── controllers/
│   ├── authController.js
│   ├── postController.js
│   └── commentController.js
├── middleware/
│   ├── auth.js
│   └── errorHandler.js
├── models/
│   ├── User.js
│   ├── Post.js
│   └── Comment.js
├── public/
│   ├── css/
│   ├── js/
│   └── images/
├── routes/
│   ├── auth.js
│   ├── posts.js
│   └── comments.js
├── views/
│   ├── layouts/
│   ├── partials/
│   └── pages/
├── .env
├── .gitignore
├── package.json
├── README.md
└── server.js
```

## API Endpoints

### Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login user
- `GET /api/auth/logout` - Logout user

### Posts
- `GET /api/posts` - Get all posts
- `GET /api/posts/:id` - Get single post
- `POST /api/posts` - Create new post (auth required)
- `PUT /api/posts/:id` - Update post (auth required)
- `DELETE /api/posts/:id` - Delete post (auth required)

### Comments
- `GET /api/posts/:postId/comments` - Get comments for a post
- `POST /api/posts/:postId/comments` - Add comment (auth required)
- `DELETE /api/comments/:id` - Delete comment (auth required)

## Scripts

- `npm start` - Start production server
- `npm run dev` - Start development server with nodemon
- `npm test` - Run tests

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**AegisCreation**

- GitHub: [@aegiscreation](https://github.com/aegiscreation)

## Acknowledgments

- Express.js documentation
- MongoDB documentation
- All contributors who helped with this project

---

Made with ❤️ by AegisCreation