# Devconnector

Small social network app built with the MERN stack. Users Login ,Like posts , share and comment as well as follow their favorite developers.
It uses Jwt and passport.js for authentication , react to build front end components ,express to run serverside code and mongoose ORM to connect to a Mongodb databse.
## Quick Start

```bash
# Install dependencies for server
npm install

# Install dependencies for client
npm run client-install

# Run the client & server with concurrently
npm run dev

# Run the Express server only
npm run server

# Run the React client only
npm run client

# Server runs on http://localhost:5000 and client on http://localhost:3000
```

You will need to create a keys_dev.js in the server config folder with

```
module.exports = {
  mongoURI: 'YOUR_OWN_MONGO_URI',
  secretOrKey: 'YOUR_OWN_SECRET'
};
```
