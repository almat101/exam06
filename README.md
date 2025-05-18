# exam06

gcc mini_serv.c

./a.out 8080

test with netcat open a new terminal

type "nc localhost 8080"

open another terminal

type "nc localhost 8080"

u should see something like this on the fist terminal:

server: client 1 just arrived

//type something on the second terminal and press enter
client 1: asd

// ctrl-c on the second terminal
server: client 1 just left

