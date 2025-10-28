# Title
# Implement Protected Routes with JWT Verification

# Objective
Learn how to secure backend API routes using JSON Web Tokens (JWT) to ensure that only authenticated users can access certain resources. This task helps you understand token-based authentication, how to verify JWTs on the server side, and how to protect specific routes from unauthorized access.

# Task Description
Create a Node.js and Express.js backend that uses JWT to protect certain API routes. Implement a login route that issues a JWT token when valid user credentials are provided (you can hardcode a sample user for simplicity). Create a middleware function that verifies the JWT token sent in the Authorization header as a Bearer token. Apply this middleware to one or more protected routes so that these routes can only be accessed if the token is valid. Test your implementation by accessing the protected route with and without a valid token to confirm that unauthorized requests are blocked and authorized requests succeed.
