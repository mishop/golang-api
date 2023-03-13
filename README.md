# Golang API test
Golang API via Chat GPT

## Video
https://youtu.be/zk35nqFW_c8

## Run server
`go run main.go`

## TEST
### POST
`curl --header "Content-Type: application/json" --request POST --data '{"username":"xyz","password":"xyz"}' http://localhost:8000/users
### PUT
`curl --header "Content-Type: application/json" --request PUT --data '{"username":"xyz","password":"xyza"}' http://localhost:8000/users/xyz`
