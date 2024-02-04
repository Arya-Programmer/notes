## کۆنترۆڵ فلۆو
لە پرۆگرامینگا کۆد دێڕ بە دێڕ ئەخوێندرێتەوە، لەسەرەوە بۆ خوارەوە بە ڕیز. وەک خەتێکی ڕێک وایە لە لایەکەوە بۆ لاکەی کە.
بەڵام ئێمە لە ڕێگەی Control structureەکانەوە ئەتوانین پێچ بکەینەوە و باز بەین.
یەکێک لەوانە:
### مەرج - if
پێی ئەوترێت conditional execution، بۆ بازیانە لە کۆدەکەیا. ئەمە دروست ئەبێت کە if بەکارئەهێنین.
```js
let price = Number();
const interest = 0.1;
if (!theNumber.isNaN()) {
	console.log("Price in four installments:" + theNumber*theNumber);
}
```
### ڕوونکردنەوە
لە دێڕی یەکەما Functionی Number نوسینەکەی ناویمان بۆ ئەکات بە ژمارە. Boolean و Stringیشمان هەیە هەمان ئیش ئەکەن بۆ تایپەکەی خۆیان.

### Curly brackets
وە ئەبینین دوای statementی مەرجییەکە، کەوانەی لوول هەیە، ئینجا ئەم کەوانانە بۆ ئەوەیە وەجبەیەک دێڕ، بە یەک expression دەرببڕین.
تەبعان ئەو کەوانانە ئەتوانی لا ببەیت، بەو حسابەی کە کە لەم کۆدەیا تەنها یەک دێڕمان هەیە، بۆیە زەڕور نییە چونکە دوو سێ دێڕمان نییە تاوەکو بە کەوانە بمانەوێ وەکو یەک دانە حسابی بۆ بکرێت. بو نموونە:
```js
if (1 + 1 === 2) console.log("1 + 1 akata 2");
```

بەڵام هەموو کاتێک من دای ئەنێم، ئێوەش وابکەن.
### Else
ئەتوانین Else بنووسین تاوەکو بڵێین ئەگەر  مەرجی یەکەم true نەبوو وەرە مەرجی دووەم.
```js
const prompt = require("prompt");


let theNumber = Number(prompt("pick a number"))
if (!Number.isNaN(theNumber)) {
    console.log("Your number divided by two is:" + theNumber/2);
} else {
    console.log("kaka wtman zhmara.");
}
```

باشە جیاوازی بەکارهێنانی ifێکی تر و else چییە؟
بۆچی هەر if statementێکی تر دانەنێین، واتە:
```js
const prompt = require("prompt");


let theNumber = Number(prompt("pick a number"))
if (!Number.isNaN(theNumber)) {
    console.log("Your number divided by two is:" + theNumber/2);
} 
if (Number.isNaN(theNumber)) {
    console.log("kaka wtman zhmara.");
}
```

لەم کەیسەیا فەرقیان نییە.
بەس فەرقی پرۆگرامینانەی هەیە.

| بە if | بە else |
|---|---|
| خۆت دووبارە ئەکەیتەوە | خۆت دووبارە ناکەیتەوە |
|هەردوو کۆدەکە ڕەن ئەبێت هەموو کاتێک | تەنها ئەو کاتە ڕەن ئەبێت کە کۆدی یەکەم false بێت |

### Chaining
ئەگەر زیاتر لە if/elseێکت ویست ئەوا ئەتوانین ڕەبتیان بکەینەوە بەیەکەوە.
```js
const prompt = require("prompt");

let theNumber = Number(4);
if (!Number.isNaN(theNumber) && (5 <= theNumber >= 10)) {
    console.log("Your number divided by two is:" + theNumber/2);
} else if (theNumber > 10) {
    console.log("Zhmaraiaki bchuktr halbzhera");
} else if (theNumber < 5) {
    console.log("toze zhmaraiaki gawratr");
}
```
ئەڵێین ئەگەر ئەوەی کە بەکارهێنەر داغڵی کردووە، ژمارەیە وە لە هەمان کاتیشا لەنێوان ٥ و ١٠ەیایە، ئەوا دابەشی دووی بکە و پشانی بە، بەڵام گەر بچووکتر بوو یان گەورەتر بوو پێی بڵێ کە بچووکترە یان گەورەترە.