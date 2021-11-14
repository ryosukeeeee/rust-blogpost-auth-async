# rust-blogpost-auth-async

original post: [Build an API in Rust with JWT Authentication using actix-web](https://auth0.com/blog/build-an-api-in-rust-with-jwt-authentication-using-actix-web/)

## Endpoints
- GET /users — returns all users
- GET /users/{id} — returns the user with a given id
- POST /users — takes in a JSON payload and creates a new user based on it
- DELETE /users/{id} — deletes the user with a given id