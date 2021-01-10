## LuckyJS

Lucky JS is meant to be a javascript npm but with some features.

## Features

|Name|Come Out|Version|Location|
|----|--------|-------|--------|
|Cookies|v1.0.0|V1.0|[Cookies](https://github.com/DJ-JR30/LuckyJS/blob/main/README.md#cookies)|
|UUIDv4|v1.0.0|V1.0|[UUID](https://github.com/DJ-JR30/LuckyJS/blob/main/README.md#uuidv4)|

### Setup
To use this npm put this at the top of your file.
```javascript
  const LuckyJS = require('luckyjs');
```


### Cookies

Cookies are mainly used in websites to check if there is a session open or need to show you a guest screen.

__Create Cookie__
```javascript
  LuckyJS.createCookie(<cookieName>, <cookieValue>, <daysToExpire>);
```

__Access Cookie__
```javascript
  LuckyJS.accessCookie(<cookieName>);
```

### UUIDv4

UUID are Universally Unique Identifier if you code for minecraft or other thpe of stuff you should know this.

__UUIDv4 Generator__
```javascript
  let x = LuckyJS.UUIDv4();
```

`x` will equal the UUID.
