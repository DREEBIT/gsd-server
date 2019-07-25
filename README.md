# GSD Server

## Installation

### File Structure

Please provide following structure:

* package.json (File - see below)
* database (Directory)
* .env (File - see below)

### package.json

````json
{
  "name": "gsd-server-module",
  "scripts": {
    "start": "node ./node_modules/@dreebit/gsd-server/dist/index.js"
  },
  "dependencies": {
    "@dreebit/gsd-server": "^0.3.0"
  }
}

````

### .env
```
PARAMETER_DATABASE=./database/parameter_database.json
DATA_DATABASE=./database/data_database.json
CONFIG_DATABASE=./database/config_database.json
PARAMETER_SERVER_URL=http://gsd.config.dreebitnet.local/export/parameter
MORGAN_CONFIG=dev
MAX_PARAMETER_VALUES=300
MODBUS_INTERVAL=500
JWT_SECRET=555NASE
MODBUS_DEBUG=false

```

## Start

```
npm start
```