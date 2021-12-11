## BACKEND INSTALLATION

1. First you must have MongoDB community or enterprise installed `mongod`
2. Then you have to open the server directory
3. Run the command `npm install` 
4. Open the `*/server/config.js` file and configure the details carefully. 
5. The `*/server/sites.json` contains the information for the initial site data you can change is or just run the command `mongoimport --drop -d cms-db -c sites sites.json` to import the initial data.
6. Now run the command `npm start` to start the server


## FRONTEND INSTALLATION

1. The client directory contains the frontend code. 
2. Open `*/client/src/config.js` file and configure it settings
3. In the client directory run the command `npm install`
4. Then run the command `npm start`

## ACCOUNT CONFIGURATION

1. After registering the account on portal open the database got to `users` collection and change the role to `admin`
