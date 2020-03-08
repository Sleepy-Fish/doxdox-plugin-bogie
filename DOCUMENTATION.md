# [doxdox-plugin-bogie](https://github.com/Sleepy-Fish/doxdox-plugin-bogie) *1.0.0*

> Bogie.js layout plugin for doxdox.


### index.js


#### plugin(data) 

Boostrap template plugin for doxdox.




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| data | `Array`  | Methods parsed using a doxdox parser. | &nbsp; |




##### Examples

```javascript
parseInputs(inputs, {'parser': 'dox', 'layout': 'bogie'}).then(content => console.log(content));
```


##### Returns


- `Promise`  Promise with generated content.




*Documentation generated with [doxdox](https://github.com/neogeek/doxdox).*
