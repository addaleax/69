# 69 – nice(2) bindings for Node.js

https://linux.die.net/man/2/nice as a JS function. That’s it, that’s the module.

```js
const nice = require('69');
nice(5);  // Increase niceness by 5.
```

(This is an alias of [nice-napi](https://github.com/addaleax/nice-napi), if you happen to need a more safe-for-work name. 🙂)
