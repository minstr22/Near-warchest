
###  Overview
NEAR Protocol is a decentralized application platform that is secure enough to manage high value assets like money or identity and performant enough to make them useful for everyday people, putting the power of the Open Web in their hands.


# NEAR Protocol Warchest Bot Stakewars Warchest bot  for monitoring and adapting the stake Ⓝ
It is warchest bot written in Go language which is used for monitoring and adapting the stake


Put the executable in the same server and directory as you participate stakewars game, such as ``~/stakewars`.
Make sure export NODE_ENV=betanet

### Requirements 
This warchest bot requires:
* Go language version 1.14.6 and higher
* near-shell install in the system where script will run.
    * To install near-shell run below command:
    `
    npm install -g near-shell
    `
* near need to be logged in shell (command)

### Build
To Build the script you need to execute the following command
`
go build main.go
`

### Run
To run the command you need to execute the command
`
./main
`


