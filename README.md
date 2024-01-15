# NodeJS - Midterm Project

**Goal:** Create a site with BREAD (Browse, Read, Edit, Add, Delete) functionality using NodeJS and Express as backend.

## Instructions

- You are free to create any type of site as long as it has CRUD/BREAD functionality and routes
- Keep the database in-memory or inside a *Model* (No external database)
- You can use and modify an existing past project
- The site must have login and signup
- Use *bcrypt* to hash and verify the password [https://www.npmjs.com/package/bcrypt]
- Use cookies to keep user information in the browser after they login. Clear the cookies when they log out
- You can choose to build your frontend using EJS, React, or Next.js

## Sample routes and requests for BREAD

- **Browse:** GET /posts
- **Read:** GET /posts/1
- **Edit:** PUT/PATCH /posts/1
- **Add:** POST /posts
- **Delete:** DELETE /posts/1

## Presentation

Individual presentation will be on January 22, 2024. During the presentation of your website, please follow this flow:

1. Signup
2. Login
3. Add an item
4. Show all items in a list
5. View individual item
6. Edit item
7. Delete item
8. Log out
