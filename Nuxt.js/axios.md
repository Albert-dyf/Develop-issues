```
RangeError: Maximum call stack size exceeded
    at assignValue (utils.js?c532:278)
    at forEach (utils.js?c532:253)
    at merge (utils.js?c532:291)
    at assignValue (utils.js?c532:282)
    at forEach (utils.js?c532:253)
    at merge (utils.js?c532:291)
    at assignValue (utils.js?c532:282)
    at forEach (utils.js?c532:253)
    at merge (utils.js?c532:291)
    at assignValue (utils.js?c532:282)
```

首先排查代码是否出错，保证无误情况下，建议检查前端依赖
在之前版本正常运行情况下，新版本无法运行的，建议删除新的依赖，回退之前的依赖版本进行尝试
