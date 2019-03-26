# unrealengine-node-wasm
🚀💥🔥Unreal Engine 4 node.js server for webassembly version

### Install
```
yarn add unrealengine-node-wasm
```

### Example
Just create a server.js file in your UE compiled to webassembly application and add:

```
const initUEServer = require('unrealengine-node-wasm');
initUEServer(".", 3000);
```