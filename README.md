# Trello clone (Freshcode)

### Run server

```
cd server && npm i && npm run dev
```

### Run client

```
npm i && npm start
```

### To Clone it ?

- git clone {this repo}
- create a mongodb Atlas Cluster and get connection uri
- make sure you have two now secrets

  - mongo_uri = "connection uri with user and password"
  - jwtsecretkey="random string"

- add a .env file and add same two secrets like .env.sample file so work in development mode.
