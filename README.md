## Installation

git pull https://github.com/Malka/CORS-Proxy.git


## Running

Standalone:

    $ ./bin/index.js
    CORS Proxy started on localhost:9292

Standalone with custom host/port:

    $ ./bin/index.js 0.0.0.0 1234
    CORS Proxy started on 0.0.0.0:1234


## Usage

The cors proxy will start at http://localhost:9292. To access another domain, use the domain name (including port) as the first folder, e.g.

    http://localhost:9292/localhost:3000/sign_in
    http://localhost:9292/my.domain.com/path/to/resource
    etc etc
