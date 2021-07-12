# Abhi-Vaadan

Abhi-Vaadan is a video chat app that makes it easy to groups up with people you want to meet.
This is a teams clone app, made during the Microsoft Engage Program 2021


Check out the live demo: https://shivangi-teams-clone.herokuapp.com/

This app is build using NodeJS, Socket.io, and Peerjs(WebRTC) and AuthO SDK.

## How to run the project?

1. Clone this repository in your local system.

2. In your local system, open terminal at that location and run ``` npm i ```.

3. Add .env file inside the folder along with other files using below structure.
    ```
    AUTHO_SECRET=a long, randomly-generated string stored in env file
    BASE_URL=http://localhost:3000
    CLIENT_ID=<CLIENT Id from AuthO config>
    ISSUER_BASE_URL=<BASE_URL from AuthO config>
    PORT=3000

    ````
4. Run ```npm start```

5. Go to your browser and type `http://localhost:3000/` in the address bar.

6. Hurray! That's it.


