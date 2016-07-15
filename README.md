## weblearn-container-sequential

Sequential container for [WebLearn]

On a forward pass, feeds the output of each module to the next module as input, from first module to last. Passes gradients backwards through modules on backward pass.

### Usage
```
npm install weblearn-container-sequential
```

```js
const Sequential = require('weblearn-container-sequential')

const model = Sequential()
  .add(layer1)
  .add(layer2)
  
model.forward( /* ... */ )
model.backward( /* ... */ )

```

[WebLearn]: https://github.com/keppel/weblearn
