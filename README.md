# Zeppelin
A decentralized marketplace for computation power

## How do I develop?
First, install the dependencies with

    $ npm install

Start running node and watching for file updates

    $ npm run watch

Node is now running on localhost:8000, and expects Ethereum JSON-RPC on localhost:8545.

## How do I release?
I don't know why we would be making any releases of this yet, but...

Build, obfuscate and minify with

    $ npm run build

Deploy on node with

    $ npm start

Success! Node is running on localhost:8000, and expects Etherum JSON-RPC on localhost:8545.

## Check the status of a mini-Zeppelin
The status is available on http://zep.qng.se.

Protocol | Port
---------|-----
SSH      | 122x
JSON-RPC | 404x
DEVP2P   | 3030x

## What is going on here?
The frontend is powered by react, written in ES6.
With docker-transfer integrated in the node server, Zeppelin should be function as our full stack solution outlined in the report, and backed up by protocol specifications in the wiki.
The frontend will then broker requests down to Ethereum, as well as communicate over whisper with workers and clients.
