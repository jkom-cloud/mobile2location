# mobile2location

### Install

`npm install jkom-cloud/mobile2location --save`

### Usage

```javascript
const m2l = require('mobile2location');

const result = m2l('17705143399');
console.log(result);
```

### Response
success

```
{ 
    prefix: '177',
    mobile: '17705143399',
    province: '江苏',
    city: '南京',
    isp: '电信',
    code: '025',
    zipcode: '210008',
    types: '电信177卡' 
}
```

error

```
false
```


