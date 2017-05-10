# WebRTC video chat app with ReactJS
## Synopsis
WebRTC audio/video conferencing app with user authentication using ReactJS.
## Motivation
Simple ReactJS app that interacts with the WebRTC APIs to establish audio/video conference between users, without a trip through a server.
## Application Logic and Implementations
To connect two users over WebRTC, we exchange information to allow browsers to talk to each other. This process is called signaling and it is facilitated by using NodeJS and socket server chained to the express 4.0 engine to provide the plumbing. Other than signaling, no data has to be sent through a server. When a connection is successfully established and authentication and authorization are complete, stream data exchanged between peers is directed to a React component for rendering.

## Installation

Once you have forked this project, go ahead and use npm through the command line to install all required dependecies:

```bash
npm install
npm install webpack -global
webpack --progress -p
npm start
```

## Demo

Demo of the app can be found on Heroku:
https://webrtc-video-room.herokuapp.com/

### License

MIT License
