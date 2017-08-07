# Env Pino

Config pino via environment variables.

## Usage

### 1. Install Package

```
npm i --save env-pino
```

### 2. Set Environments

```
export PINO="{\"prettyPrint\": true}"
```

or

```
export PINO_PRETTY_PRINT=true
export PINO_LEVEL=error
```

Note: the latter format will override the corresponding fields defined in the former format.

### 3. Use Pino

```

const logger = require('env_pino')

// logger is already configged via env variables
logger.info('...')
```

## Reference

- [All available pino options](http://getpino.io/#/docs/API?id=constructor)

## License

MIT