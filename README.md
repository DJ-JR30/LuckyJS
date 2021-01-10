## LuckyJS

Lucky JS is meant to be a javascript npm but with some features.

## Features

|Name|Come Out|Version|Location|
|----|--------|-------|--------|
|Cookies|v1.0.0|V1.0|[Cookies](https://github.com/DJ-JR30/LuckyJS/blob/main/README.md#cookies)|

### Setup
To use this npm put this at the top of your file.
```javascript
  const LuckyJS = require('luckyjs');
```


### Cookies

Cookies are mainly used in websites to check if there is a session open or need to show you a guest screen.

__Create Cookie__
```javascript
  LuckyJS.createCookie(<cookieName>, <cookieValue>, <daysToExpire>)
```

__Acces Cookie__
```javascript
  LuckyJS.accessCookie(<cookieName>);
```
