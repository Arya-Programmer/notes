### Switch statement
```js
if (x === "value1") action1(); 
else if (x === "value2") action2(); 
else if (x === "value3") action3(); 
else defaultAction();
```
زۆرکات کۆدەکەت بەم شێوەیەی لێیەت، باشتر لەم جۆرە نووسینەی هەموو ifە statementێکی کەمان هەیە پێی ئەوترێ switch statement.
```js
switch (prompt("7alw waz3?")) { 
	case "Bashm": console.log("Yaxwa har bashbi"); break; 
	case "Xrapm": console.log("Bo? Chibwa?"); 
	case "Sarm eshe": console.log("Bro piasaiak bka."); break; 
	default: console.log("Kaifi xota"); break; 
}
```
تەبعان switch statementەکە شتەکەی بۆ سادەتر نەکردینەوە، ئەمە یەکێکە لە کێشەکانی زمانی جاڤاسکریپت.
هەر ifەکە بەکاربێنی باشترە زۆربەی کات. من خۆم زۆر کەم switch بەکارەهێنم چونکە هەموو ئیشێک بە if دەبر ئەبێ.

لەم switchەی سەرەوەیا، چێک ئەکاتەوە بزانێ بەکارهێنەر چی داغڵ ئەکات و موقارەنەی ئەکات بە کەیسەکان ئەگەر هیچکامیان نەبوو ئەچێت بۆ کۆتا دانە کە نووسراوە default، ئەو breakانەش لە کۆتاییا بۆ ئەوەیە کە switchەکە بێتە دەرەوە، لە case دووەم breakمان نییە بۆیە ئەگەر caseی دووەم runبکرێت ئەوا خۆی یەکسەر دێڕی دوای ئەویش run ئەکات.

### Naming
ناولێنان، چەن جۆرێکی هەیە:
```js
fuzzylittleturtle
fuzzy_little_turtle 
FuzzyLittleTurtle
fuzzyLittleTurtle
```
من خۆم ئەوەی کۆتا بەکارەهێنم پێی ئەوترێت Lower camel case.

### Comment
کۆمێنت کردن: shortcut (Ctrl + /)
```js
// This is a comment
```

کۆمێنت کردن بۆ زیاتر لە دێڕێک:
```js
/*
This is 
a
multi
line
comment
*/
```

![[TotalHoursWastedHere.png]]