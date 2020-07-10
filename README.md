# GoCLC
GoCLC is a command line, multi-user chat server and client written in, you guessed it, Go!

## To Run Your Own Server
Clone the repo, then execute `go run .` in the project's root directory. The server will begin running, listening on `localhost:8000`.

Since GoCLC is currently in the early stages of development, the server cannot do much more than greet a user and offer rudimentary commands. However, this will change rapidly, so keep an eye on this repo!

## To Run the Test Suite
Execute `go test server/...` to run all tests related to the server code.

## Planned Features
General chat\n
\#Channel based chat\n   
Private messaging between clients\n
Encrypted message passing between client-server-client
