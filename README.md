### jquery-cookie
---
https://github.com/carhartl/jquery-cookie

```
<script src="/path/to/jquery.cookie.js"></script>
```

```js
$.cookie('name', 'value');

$.cookie('name', 'value',  { expires: 7 });

$.cookie('name', 'value', { expires; 7, path: '/' });

$.cookie('name');
$.cookie('nothing');

$.cookie();

$.removeCookie('name');
$.removeCookie('nothing');
$.cookie('name', 'value', { path: '/' });
$.removeCookie('name');
$.removeCookie('name', { path: '/' });

$.cookie.raw = true;
$.cookie.json = true;

expires: 365
path: '/'
domain: 'example.com'
secure: true

$.cookie('foo', '42');
$.cookie('foo', Number);
$.cookie.raw = true;
$.cookie('foo', unescape);
```

```
```

