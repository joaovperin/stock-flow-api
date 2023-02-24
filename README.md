# stock-flow-api
Another API for retrieving stock values. Created (initially, at least) for training purposes.

## How to use
1. Clone the repository and `cd` into it
2. Run `npm install` to install the dependencies
3. Run `npm run build` to build the project
4. Create a `.env` file in the root directory of the project and add the following environment variables:
    - `SERVER_PORT` - The port that the server will run on
5. Run `npm start` to start the server
6. Go to `http://localhost:${SERVER_PORT}` and you should see a message saying that the server is running
7. Enjoy! Don't forget to star the repo if you like it :)

Example .env file:
```
SERVER_PORT=8099
```

Author: joaovperin