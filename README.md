# loop.js
Part of a knot. Loop is a bare-bones pub/sub style event emitter. Inspired by [knot.js](https://github.com/callmecavs/knot.js).

## Install
```javascript
npm i loop.js --save
```

## Usage
```javascript
import loop from 'loop.js'

const events = loop()

events.on('print', msg => console.log(msg))

events.emit('print', 'Hello World!')

// logs 'Hello World!'
```

MIT License
