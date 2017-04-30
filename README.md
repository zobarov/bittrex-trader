# JavaScript Dev Environment Setup

Preconfigured setup for JavaScript projects on Node.js

## Built With

* Node + NPM environment
* WebServer: Express
* Transpiler: BABEL
* Bundling: Webpack
* Linting: ESLint
* Testing framework: Mocha
* Testing Assertion Library: Chai
* Testing Helper Library: JSDOM
* CI: Travis
* HTTP Mocking: JSONServer, JSON Schema Facker

## Usage

To enable dependencies vuolnurability check:
* npm install -g  nsp
    nsp check 
    
To run with config:
* node buildScripts/srcService.js

Localtunnel to quick share progress:

* npm install -g localtunnel
* lt --port 3000 --subdomain alex

Start with linting watch:
* npm start -s
