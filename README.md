## AuthApp

## STACK
Front end stack
- [React.JS](https://reactjs.org/) - For building UI.
- [Redux](https://redux.js.org/) - State Management Middleware.

Back end stack
- [Express.JS](http://expressjs.com/) - Express.JS for building server APIs.
- [Passport](https://http://passportjs.org/) - For Google OAuth Strategy

# Intstructions
Create a config folder and inside it create a keys.js file.<br>
```
module.exports = {
    googleClientID: 'process.env.GOOGLE_CLIENT_ID' ,
    googleClientSecret: 'process.env.GOOGLE_CLIENT_SECRET',
    facebookClientID: 'process.env.FACEBOOK_CLIENT_ID',
    facebookClientSecret: 'process.env.FACEBOOK_CLIENT_SECRET',
    mongoURI: 'process.env.MONGO_URI'
}
```

In the root folder create an .env file and add
```
GOOGLE_CLIENT_ID=value from google apis
GOOGLE_CLIENT_SECRET=value from google apis
FACEBOOK_CLIENT_ID=value from facebook apis
FACEBOOK_CLIENT_SECRET=value from facebook apis
MONGO_URI=value form mlab
```

## To run
npm install<br>
cd client<br>
npm install<br>
cd ..<br>
npm run dev

Access the application at: http://localhost:3000/login while server is running at port 5000.