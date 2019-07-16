### chainradar-api
---
https://github.com/yasaricli/chainradar-api

https://www.npmjs.com/package/chainradar

```js
var ChainRadar = require('chainradar');

var api = new ChainRadar(options)

api.getStatus((data) => {
  console.log(data.hash)
});

const blockOptions = {
  from: '100000',
  to: '100001'
};

api.getBlocksData(blockOptions, (data) => {
  console.log(data)
});

api.getBlockHeader('xxx', (data) => {
  console.log(data)
});

api.getBlockData('xxx', (data) => {
  console.log(data)
})

api.getTransactionData('xxx', (data) => {
  console.log(data)
})
```

```sh
npm install chainradar
npm run prepublish
```

