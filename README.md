# black-pearl-client

Ultra simple client to push metrics in a Elastic Search + Kibana.

## Install

```
npm install black-pearl-client
```

## Usage

```javascript
var blackPearl = require('black-pearl-client');
var client = blackPearl.createClient('http://localhost:9400');

client.push('connectedUsers', { count: 5 });
```

![screen shot 2013-12-24 at 01 15 48](https://f.cloud.github.com/assets/266302/1803923/a9ffa908-6c30-11e3-8309-97b8f7f5e6d1.png)

## License

MIT