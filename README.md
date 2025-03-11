Full Stack Blog App Using Next.js & MongoDB

This is a full-stack blog application built using Next.js for the frontend and backend, along with MongoDB for database management. The project includes an admin panel, a responsive frontend with HTML and CSS, and backend routing for seamless navigation between different sections of the website.

Features
Next.js for Full Stack Development: Combines frontend and backend in a single codebase.
MongoDB for Database Storage: Stores blog posts, user details, and admin data.
Admin Panel: Manage blog posts and users from a dedicated admin interface.
Responsive Frontend: Styled using HTML and CSS for an engaging UI/UX.
Backend Routing: Enables navigation between different pages dynamically.

Local Development Server: Runs at http://localhost:3000.
Installation and Setup
Prerequisites
Ensure you have the following installed:
Node.js
MongoDB

Steps to Run the Project
Clone the Repository:
git clone https://github.com/your-github-username/next-blog-app.git
cd next-blog-app
Install Dependencies:
npm install

Configure Environment Variables:
Create a .env.local file in the root directory and add your MongoDB connection string.

npm run dev
The application will be available at http://localhost:3000.

Project Structure
next-blog-app/
├── app/
├── Assets/
├── Components/
│   ├── BlogItem.jsx
│   ├── BlogList.jsx
│   ├── Footer.jsx
│   ├── Header.jsx
├── node_modules/
├── public/
├── .gitignore
├── eslint.config.mjs
├── jsconfig.json
├── next.config.mjs
├── package.json
├── package-lock.json
├── postcss.config.mjs
├── README.md
├── tailwind.config.mjs

