This project is a FastAPI-based backend service for managing a personal portfolio website. It provides endpoints to create, read, update, and delete projects, blog posts, and contact information, all stored in an SQLite database. The API is designed to be easily integrated with a frontend to showcase your work, blog posts, and contact information.

Features
Projects: Manage your portfolio projects with CRUD operations.
Blog Posts: Create and manage blog posts.
Contact Information: Store and update contact details.
Technologies Used
FastAPI: A modern, fast (high-performance) web framework for building APIs with Python 3.7+.
SQLite: A lightweight, disk-based database, which is simple to set up and use.

API Endpoints

#Projects
#Create a new project: POST /projects/
#Retrieve all projects: GET /projects/
#Retrieve a specific project: GET /projects/{project_id}
#Update a project: PUT /projects/{project_id}
#Delete a project: DELETE /projects/{project_id}

#Blog Posts
Create a new blog post: POST /blog_posts/
Retrieve all blog posts: GET /blog_posts/
Retrieve a specific blog post: GET /blog_posts/{blog_post_id}
Update a blog post: PUT /blog_posts/{blog_post_id}
Delete a blog post: DELETE /blog_posts/{blog_post_id}

#Contact Information
Add contact information: POST /contact_info/
Retrieve all contact information: GET /contact_info/
Retrieve specific contact information: GET /contact_info/{contact_info_id}
Update contact information: PUT /contact_info/{contact_info_id}
Delete contact information: DELETE /contact_info/{contact_info_id}
