### دووبارەبوونەوە - loop
پێی ئەوترێت loop execution، بۆ پێچکردنەوەیە بۆ دواوە لە کۆدەکەیا.
با بڵێین یەکێک پێت ئەڵێت عەزێت نەبێ تاوەکو ژمارە ١٥، ژمارە جووتەکانم پشان بە.
```js
console.log(0);
console.log(2);
console.log(4);
console.log(6);
console.log(8);
console.log(10);
console.log(12);
console.log(14);
```

### While
لە ڕێگەی statementی whileەوە ئەتوانین وەجبە دێڕێک دیاری بکەین لە ڕێگەی براکێتی لوولەوە بۆ ئەوەی دووبارە بێتەوە.
لە while وەکو if مەرجەکە ئەنووسین لەناو کەوانە دوای whileەکە.

```js
let counter = 0;
while (counter < 5) {
    // anything here will be repeated 5 times.
    console.log(counter); 
    counter = counter + 1; // Or counter++
}
```

پاشان بابەتی دواترمان do loopە.
تاکە فەرق ئەوەیە کە لە هەموو حاڵەتێکا یەک جار ناو curly bracketەکە ڕەن ئەکات.
```js
const prompt = require("prompt-sync")();

let yourName;
do {
    yourName = prompt("who are you?");
} while (!yourName)
console.log(yourName);
```
نیشانەی ! کەیسەکە هەڵئەگەڕێنێتەوە. واتە فاڵس ئەکات بە ترو وە بە پێچەوانەشەوە. تەزبیحەکانیش هەموویان trueن بێجگە لە "".

### indentation and spacing
1. لە پێش و پاش یەکسانە بۆشایی بکە دایمەن.
2. لە پێش و پاش curly بۆشایی بکە دایمەن.
3. لە کۆتاییا یان ; دابنێ یان دایمەنێ بە consistentی.
4. کۆدەکانت ئیندێنت بکە.

### For loop
لەبەر ئەوەی زۆربەی زۆری بەکارهێنانەکانی loop ژمارەی دووبارەبوونەوەکان دیاری ئەکرێت. بۆیە لەجیاتی بە while و counter ڕێگەیەکی کورتر هەیە ئەویش For loop.

```js
for (let number = 0; number <= 12; number = number + 2) {
    console.log(number);
}
```

### دەرچوونەکان
دەرچوون لە دووبارەبوونەوەکان، تەبعان ڕێگەیەکی کەمان هەیە بۆ دەرچوون لە loop جگە لەوەی کە ئەگەرەکەی بکاتە false. بە بەکارهێنانی break statement ئەتوانین لە loopەکە بێینە دەرەوە.
بابڵێین ئەتەوێ بەدوای ژمارەیەکا بگەڕێی کە دابەشی ٧ ئەبێت لە نێوان سفر تا ٢٥.
```js
for (let current = 0;; current = current + 1) {
	if (current % 7 === 0) {
		console.log("Number: " + current + "is divisible by 7");
		break;
	}
}
```
تەبعان ئەگەر ئەو if statementە لابەین و ئەو breakە نەمێنێ ئەوە کۆدێک ئەنووسی کە هەتا هەتایە run ئەکات و بەس ئەوکاتە ئەوەستێ کە RAMەکەت شوێنی نەماوە.

#### continue
ئەمیش وەکو break وایە و لەناو loop بەکارەهێنرێت، جیاوازییەکەی ئەوەیە لەباتی لە تەواوی loopەکە بێتە دەرەوە تەنها یەک هەنگاو ئەپەڕێنێت.

### Updating a binding
لە loopدا خێراترین ڕێگەمان بۆ ئەوەی variableەکە بگۆڕین ئەمەیە:
```js
for (let current = 0; current <= 5; current += 1) console.log(current);
```
 لەوە کورتتر:
 ```js
 for (let current = 0; current <= 5; current++) console.log(current);
```
