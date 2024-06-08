# Social Media Platform
A simple application to handle users, posts, and comments

## Requirments 
1. Define a Sequelize model for users with the following fields: username, email, and password.
2. Define a Sequelize model for posts with the following fields: title, content, and author (linked to the User model).
3. Define a Sequelize model for comments with the following fields: content, postId (linked to the post model), and userId (linked to the User model).
4. Implement routes and controllers for user registration, login, and logout. (email must be unique)
5. Implement routes and controllers for creating, reading, updating, and deleting posts.
6. Implement routes and controllers for creating, reading, updating, and deleting comments.
7. Ensure that users can only edit or delete (soft delete) their posts.
8. Use bcrypt.js to securely hash and store user passwords.
9. Special endpoint to get a specific user with a specific post and post’s comments.
10. Get a specific post with the author.

## Deployment
- Database on clever-cloud.com
- Application on Render: https://social-media-platform-4anw.onrender.com

## Documentation 
### [Postman](https://documenter.getpostman.com/view/34627138/2sA3XJmkVc#9a80206f-430e-49df-8ed3-ea4e8f965196)

## Schema
![ERD](https://github.com/tasbeehismail/social-media-platform/blob/main/diagrams/schema.png)
