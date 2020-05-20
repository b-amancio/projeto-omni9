# projeto-omni9
App code developed for study purposes, at the "Semana OmniStack 9.0" event from [RocketSeat](https://rocketseat.com.br/).

The project consists of a web platform to register spots, and a mobile application where developers will schedule a date to use them (scheduling in real time).

### Stack
*Front*  : Axios, ReactJS, Socket.io

*Back*   : MongoDB, Node.js, Mongoose, Express, Socket.io, Multer

*Mobile* : React Native, Axios, Expo, Socket.io

## Configure
#### Back end
- (to make changes, create a cluster at [MongoDB Atlas](https://www.mongodb.com/cloud/atlas), and configure *mongoose* connection at a file on **backend/src/server.js**
- `$ npm i`
- `$ yarn dev`
- the start port will be **3333**
#### Front end
- `$ npm i`
- `$ yarn start`
- the start port will be **3000**
#### Mobile
- `$ npm i`
- `$ yarn start`
- the start port will be **19002**, and Expo client on **exp://YourLocalIP:19000**
