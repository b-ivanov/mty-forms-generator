# Forms generator
A simple project for generating forms with data, created during the "Mentor the young" program.

# Start up
### Frontend
1. Navigate to the client folder and install all dependacies using:
```bash
npm install
```
2. Build the client app using:
```bash
npm run build
```
Available also in wathc mode:
```bash
npm run build:watch
```
3. To run the client app locally and open the project in a new browser tab:
```bash
npm run serve
```

### Backend
1. Navigate to the server folder and install all dependacies using:
```bash
npm install
```
2. Create a Mongo DB account an a free cluster from [MongoDB's site](https://account.mongodb.com/).
3. Create a .env file with the following properties:
```
DB_USERNAME=[Mongo DB username]
DB_PASSWORD=[Mongo DB password]
DB_CLUSTER_URL=[Mongo DB cluster URL]
PORT=[Prefered port number (8080)]
```
4. Run command for database creation (can be used for reset as well):
```bash
npm run db:reset
```
5. To run the server locally and open the project in a new browser tab:
```bash
npm start
```

# Tech stack
### Frontend
- [Lit](https://lit.dev/)
- [Web Components UI5](https://sap.github.io/ui5-webcomponents/)
- [Zod](https://zod.dev/)
### Backend
- [TypeORM](https://typeorm.io/)
- [MongoDB](https://www.mongodb.com/)
- [Express JS](https://expressjs.com/)