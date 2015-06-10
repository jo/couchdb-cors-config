# CouchDB CORS Configuration
This repository hosts a single JSON file holding the required CORS configuration
settings, which have been taken from
[pouchdb/add-cors-to-couchdb](https://github.com/pouchdb/add-cors-to-couchdb)

You can push the configuration to CouchDB via
[couchdb-configure](https://github.com/eHealthAfrica/couchdb-configure):

## Installation
```sh
npm install --global couchdb-configure
```

## Push Configuration
```sh
couchdb-configure http://localhost:5984 _config.json
```

You can also include this file in your project as part of a
[couchdb-bootstrap](https://github.com/eHealthAfrica/couchdb-bootstrap)
directory.
