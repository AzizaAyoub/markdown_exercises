### Solution 
``` JavaScript 
compareByLength('patience', 'perseverance'); // -1
compareByLength('strength', 'dignity');      //  1
compareByLength('humor', 'grace');           //  0

function compareByLength(string1, string2) {
  if (string1.length < string2.length) {
    console.log(-1);
  }else if (string1.length > string2.length) {
    console.log(1)
  }else if (string1.length === string2.length) {
    console.log(0);
  }
}
```
