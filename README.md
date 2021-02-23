# Building Video Chat Apps using WebRTC and Golang

Code for the DSC KIIT Workshop "WebRTC + Golang" conducted on 23rd Feb 2021

PPT available [here](https://app.pitch.com/app/presentation/6371a8aa-a4ec-44ea-a9cc-432a66726150/2ad0e236-a776-4b2f-9d24-abc0245819cb)

### Frontend

The `client` is written in React and uses [Vite](https://vitejs.dev/) for the dev server. Run the following commands in the `client` directory

* `npm i` to install all the dependencies
* `npm run dev` to start the local dev server

### Backend

Written in Go. A simple WebSocket server for signalling implemented using 
[gorilla/websocket](https://github.com/gorilla/websocket)

* `go build` to compile and build the binary
* `./video-chat-app` to run the backend server on `:8000`

<br>

[![forthebadge](https://forthebadge.com/images/badges/made-with-go.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)
