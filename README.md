# Simple CRUD application with Golang
Hello this is a simple project crud application what i learn so far with golang ^_^


### Installation
Make sure golang already installed in your computer,
Install the dependencies and devDependencies and start the server.

```sh
$ git clone https://github.com/nagacoder/rest-api.git
$ cd rest-api
$ go run main.go
```
### ENDPOINT

After your run the server you can test the endpoint with postman, 
this is endpoint services ready to get test

| METHOD | ENDPOINT | PARAMS
| ------ | ------ |------ |
| GET | http://localhost:2223/users |-|
| GET | http://localhost:2223/users/ |id|
| POST | http://localhost:2223/users |name,email,address|
| PUT | http://localhost:2223/users/ |id ,name,email,address|
| PATCH | http://localhost:2223/users/ |id ,name,email,address|
| DELETE | http://localhost:2223/users/ |id|
