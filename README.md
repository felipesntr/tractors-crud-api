# Tractors CRUD API

### How to build

    You first have to up a mongodb server.
        mongodb://localhost:27017/tractors
        is the actual development database.

    npm install
    npm run build
    npm start

### How to test

    npm test

### Endpoint

    POST /save
        body: {
            "name": "",
            "image_base64": ""
        }
