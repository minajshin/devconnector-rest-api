# DevConnector - Restful API Server

```diff
+ This porject is in progress.
```

DevConnector is a social network for developers built with Node.js, Express and MongoDB. This repository includes RESTful API server code of DevConnector. It allows users to get the list of all registered developers, profile of each developer, and provides CRUD functionality for post, comment and like.

## Quick Start

#### 1) Clone the repository

```
$ git clone https://github.com/minashin/devconnector-backend.git
```

#### 2) Install dependencies

```
$ cd devconnector-backend
$ npm install
```

#### 3) Modify default.json

You will need to create a default.json in the config folder with

```
{
  "mongoURI": 'YOUR_OWN_MONGO_URI',
}
```

#### 4) Run server

```
$ npm run backend
```

## REST API Routes

#### Users:

| Route          | Description     |
| -------------- | --------------- |
| POST api/users | Register a user |

#### Auth:

| Route        | Description         |
| ------------ | ------------------- |
| GET api/auth | Get a user by token |

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Disclaimer

While this project is originally from "MERN Stack Front to Back" course on Udemy, I changed some codes for my sake. If you want to see the original code, please refer to [here](https://github.com/bradtraversy/devconnector_2.0/tree/originalcoursecode).
