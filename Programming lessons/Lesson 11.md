 ### کۆمەڵە کۆد - Function
تەبعان Function زۆر ئیسفادەی هەیە، وا ئەکات زۆر خۆمان دووبارە نەکەینەوە، هەرکاتێک هەستت کرد هەمان کۆد ئەنووسیتەوە ئەوا کۆدەکە بخەرە Functionێکەوە و Functionەکە بانگبکەرەوە.

### Defining a Function
هەر وەکو variableێکی ئاسایی ناوی ئەنێن.
```js
const square = function(x) {
    return x * x;
};

console.log(square(4)); // 16
```

لە ڕێگەی keywordی `function`ەوە ئەتوانین functionێک دروست کەین وەکو variableێکی ئاسایش ناوی ئەنێین. function کۆمەڵێ parameterی هەیە. (لەم نموونەیەی سەرەوەیا تەنها `x`).
وە bodyەکیشی هەیە کە لەناو `{}` هەموو codeەکانی کە ئەتەوێت run بکەن لەگەڵ بانکردنی functionەکەیا لەویا ئەینووسی.

### Non-Return

```js
const callCustomer = function() {
    console.log("!وەرنەوە بۆ شوتی")
}

callCustomer(); // وەرنەوە بۆ شوتی
```

ئەمە جۆرێکی functionە کە هیچ ناگەڕێنێتەوە. بەڵام کارێک ئەنجام ئەیات هەر.

### Return
```js
const power = function(base, exponent) {
    let result = 1;
    for (let count = 0; count < exponent; count++) {
        result *= base;
    }
    return result
};

console.log(power(2, 10));
// 1024
```

ستەیتمێنتێکی کە ئەبینین، پێی ئەوترێت return statement، ئیشی ئەوەیە کە functionەکە لەویا کۆتایی پێبێنێت و ئەو valueە بگەڕێنێتەوە کە 





