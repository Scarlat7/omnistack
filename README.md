# omnistack

Project for the Omnistack Week 11.0: a simple app to connect people to the right causes. Built with Node, React and React Native.


# Usage

Pre-requisites:
- node v12.16.1
- npm v6.13.4

To properly use the app, the backend server must be up while the frontend and/or the mobile app are in use.

## Backend

All below commands are executed from repository root. 

To install:

```
cd backend && npm install
```

To run the backend server:

```
cd backend && npm run start
```

To run tests defined at `./backend/tests`:

```
cd backend && npm run test
```


## Frontend

All below commands are executed from repository root. 

To install:

```
cd frontend && npm install
```


To compile and run the frontend:

```
cd frontend && npm run start
```

## Mobile

Before using the mobile app, the IP of the backend server must be updated in the `mobile/src/services/api.js` file, to properly point to your computer. This IP must the public IP of the computer running the backend server. Change the IP between angle brackets in the file:

```javascript
  baseURL: 'http://<<<<<192.168.15.6>>>>>:3333'
```

All below commands are executed from repository root. 

To install:

```
cd mobile && npm install
```

To compile and run the mobile app with Expo:

```
cd mobile && npm run start
```

The application then is available in the mobile device by scanning the QR code printed on screen with the [Expo app](https://expo.io/tools).





