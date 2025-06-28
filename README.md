# Social-Media-Application



 🚀 Features

- 🔐 User Registration and Login with JWT-based authentication
- 📝 Create, update, and delete posts
- ❤️ Like and unlike posts
- 💬 Add and remove comments
- 🖼️ Media upload support (profile pictures, post images)
- 🧾 Secure routes using middleware
- 📦 REST API architecture


 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose
- **Auth:** JWT, bcrypt
- **File Handling:** Multer
- **Environment Variables:** dotenv

 
 🧪 API Endpoints (Sample)
   Users
- `POST /api/register` – Register new user
- `POST /api/login` – Authenticate user
- `GET /api/users/:id` – Get user profile

   Posts
- `POST /api/posts/` – Create a post
- `GET /api/posts/` – Get all posts
- `PUT /api/posts/:id` – Update a post
- `DELETE /api/posts/:id` – Delete a post
- `POST /api/posts/:id/like` – Like/unlike a post
- `POST /api/posts/:id/comment` – Add a comment

