# DevConnector

## Setup Instructions

To run this project, follow these steps:

1. Run `npm i` in the root directory of the project.
2. Run `npm i` in the `client` folder of the project.
3. Create a `default.json` file in the `config` folder of the project.
4. Add the following code to the `default.json` file:

```json
{
  "mongoURI": "mongodb://localhost:27017/my-database",
  "jwtToken": "dkhasdhahksdkasjdajskdjasdjk"
}
```
5. Start the server by running node `server.js` in the root directory of the project.
6. Open a web browser and navigate to `http://localhost:3000` to view the application.

**Note:** You may need to replace `mongodb://localhost:27017/my-database` with your own MongoDB connection string. You can also generate a new JWT token by using a tool like `jsonwebtoken`.
