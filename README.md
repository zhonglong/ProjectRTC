# ProjectRTC

## WebRTC Live Streaming

- Node.js server
- Desktop client
- [Android client](https://github.com/pchab/AndroidRTC)

You can also check this iOS client from Digix Technology:

- [iOS client](https://github.com/digixtechnology/iOSRTC)

The signaling part is done with [socket.io](socket.io).
The client is built with [angularjs](https://angularjs.org/).

## Install

It requires [node.js](http://nodejs.org/download/)

* git clone https://github.com/pchab/ProjectRTC.git
* cd ProjectRTC/
* npm install
* node app.js

The server will run on port 3000.
You can test it in the (Chrome or Firefox) browser at localhost:3000.

## Author

- [Pierre Chabardes](mailto:pierre@chabardes.net)
- [Zhonglong Chen](mailto:zhonglong.chen@tpv-tech.com)

## openssl

* genrsa -out private.pem 2048
* req -new -key private.pem -out csr.pem
* x509 -req -in csr.pem -signkey private.pem -out csr.crt
