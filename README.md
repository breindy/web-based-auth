### Web Based Authentication
#### Types of Implementation Available
1. Sessions (Cookies, Session ID)
2. Tokens (JWT, OAuth & OpenID, Passport.js)

Check the different branches for the implementations below
**session** branch
**token** branch

#### Session based Authentication
**Libraries**
- express
- express-session: acts as a session middleware for express
- body-parser: middleware to work with the body of the request to register/login users
- connect-redis: provides Redis session storage for Express

**Dev Dependencies**
- Nodemon: live reload
- Standard: linting style guide

#### Token based Authentication
**Libraries**
- express
- mongoose: ORM to store models into MongoDB Cluster
- dotenv: store db configuration information
- jwt: token for authorization
- bcryptjs: hash stored password of users

**Dev Dependencies**
- Nodemon: live reload