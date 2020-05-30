# NodeJS + Express

## Users APIRest (base)
### Methods
- GET
- POST
- PUT 
- DELETE


| Entity  |End point  | GET  | POST  | PUT | DELETE  |
| :------------ | :------------ | :------------ | :------------ | :------------ | :------------ |
|  Users | /users  |  List users |  New user <br>{'username':'', password:''} | * Update user |  - |
|   | /users/:id  |  * Get user |  - | -  |  * Delete user |
|   |  /login |  - |  Login user <br>{'username':'', password:''}  | -  |  - |

*Required authentication
```
headers: {
	'x-access-token': 'value',
	'Content-Type': 'application/json'
}
```

## Clone the app
```
git clone url app
```
## Clone the app
```
cd app
```

## Create a .env file:
```
SERVER_HOST=0.0.0.0
SERVER_PORT=8080
SECRET=my-secret-key
```

## Run the app

### Install the app
```
npm install
```
### Execute
```
npm start
```
or
```
node index.js
```

## To test
```
npm run test[:watch]
```