# Steps to run the server
1. Run `npm i` command
2. Setup database and app settings inside `.env` file
3. Run `npm start` command

# Example of .env file
```
DB_USERNAME=[Mongo DB username]
DB_PASSWORD=[Mongo DB password]
DB_CLUSTER_URL=[Mongo DB cluster URL]
PORT=[Prefered port number (8080)]
```

# Endpoints
Path			| Type	| Description
--------------- | ----- | -------------------------------------------
/				| GET	| Test endpoint to check if server is running
/users			| GET	| Endpoint for retrieving all users
/users/:id		| GET	| Endpoint for retrieving an user by id
/users/:id		| PUT	| Endpoint for updating user data by id
/users/create	| POST	| Endpoint for creating a new user
/forms			| GET	| Endpoint for retrieving all forms
/forms/:name	| GET	| Endpoint for retrieving a form by name