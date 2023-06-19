# StartupEvents.registry (block)

## Basic Format
```js
StartupEvents.registry('block', event => {
  event.create()
})
```

---

### `event.create(id)`

PARAMETERS:  
　**id** (string)  
RETURN TYPE:  
　**BlockBuilder** (Internal.BasicBlockJS$Builder)