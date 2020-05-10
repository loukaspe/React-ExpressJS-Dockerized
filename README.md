###### **EXPRESS.JS / REACT.JS  DOCKERIZED** 

Back-End comes with installed:
 
a. Express JS
 
b. Mongo and MongoExpress
 
c. Redis and RedisCommander

Front-End comes with installed:
 
a. React JS

Notable Dependencies:
(BACK-END)
- **Morgan** for Logging
- **Pub** as Template Engine
- **Dotenv** for Environmental Variables
- **JWT** & **bcrypt** for secure User Authentication

Notable **DEV** Dependencies:
(BACK-END)
- **jest** for Testing
- **nodemon** for hot reloading

Notable Dependencies:
(FRONT-END)

Notable **DEV** Dependencies:
(FRONT-END)

**Installation and First Run**: 

1. Go to terminal and run ``cd development-environment``
2. In _docker-compose.yml_ in the 'mongo' container set your preferred username and password to 
`MONGO_INITDB_ROOT_USERNAME` and `MONGO_INITDB_ROOT_PASSWORD` variables. The same one must be set to .env files 
in `MONGO_USERNAME` and `MONGO_PASSWORD` variables respectively 
3. Run ``docker-compose up --build``
4. In the browser go to ``localhost:8078`` to check the backend and to ``localhost:3000`` to check the frontend