# HDR_MVP_Gateway_Auth_Web_Server

This application provides an Node Express webserver, which enables the React Application to be served.

It also handles the user login & registration through the Open Athens gateway.

### Installation

This is a node application, all node modules are installed locally.

Download or clone from Code Repsitory

[Bitbucket Repository](https://TrevorWardCIC@bitbucket.org/hdr_mvp_gateway/hdr_mvp_gateway_auth_web_server.git)

from the downloaded directory run

npm install

This will install the application on port 5003 by default.

#### .env file

Create an environment file with the following options:

_NODE_ENV_

> use local when developing
> _PORT_
> The main port should be 5003
> _APPLICATION_PATH_
> The actual path to the react application build directory
> i.e. C:\Users\TREVORWard\HDR_Gateway\Development\hdr_mvp_gateway_web_application\build

### Running the Application

`npm run dev`

> Runs the application in node watch mode

`npm start`

> runs the application without monitoring

### Other commands
