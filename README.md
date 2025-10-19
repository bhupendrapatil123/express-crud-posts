# Express CRUD Posts App

A simple Node.js and Express.js application that allows users to **Create, Read, Update, and Delete (CRUD)** posts. Each post has a unique UUID for identification and EJS templates for rendering the frontend.

---

## Features

- View all posts
- View a single post in detail
- Create a new post
- Edit a post
- Delete a post
- UUID for unique post IDs
- EJS templates for frontend
- Method-override to support PATCH and DELETE via HTML forms

---

## Folder Structure

express-crud-posts/
├── public/ # CSS and static files
├── views/ # EJS templates (index, new, show, edit)
├── index.js # Main Express server
├── package.json
├── package-lock.json
└── .gitignore


---

## Installation & Run Locally

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/express-crud-posts.git
cd express-crud-posts

2. Install dependencies:

npm install


3. Start the server:

node index.js


4. Open in your browser:

http://localhost:8080/posts

Dependencies

express
ejs
uuid
method-override

Usage

View all posts – Go to /posts.
Create a post – Click "Create New Post" → Fill username and content → Submit.
Edit a post – Click "Edit" next to a post → Update content → Submit.
Delete a post – Click "Delete Post" next to a post.
View post details – Click "See in Detail" to view a post’s full details.

Author
Your Name / GitHub: @bhupendrapatil123


---

✅ **How to Add It to GitHub**

1. Create a file in your project root called `README.md`.  
2. Paste the above content.  
3. Commit and push:

```bash
git add README.md
git commit -m "Add README"
git push

