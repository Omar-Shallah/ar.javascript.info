# البحث عن أعداد صحيحة غير سالبة
هناك سلسلة من الأعداد الصحيحة.
أنشئ تعبيرًا عاديًا لا يبحث إلا عن الكلمات غير السلبية (يُسمح بصفر).

مثال للاستخدام:
```js
let regexp = /your regexp/g;

let str = "0 12 -5 123 -18";

alert( str.match(regexp) ); // 0, 12, 123
```
