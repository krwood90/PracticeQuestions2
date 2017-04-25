# PracticeQuestions2
Java



1.Write a function min that takes two arguments and returns their minimum
```javascript
function min(a,b) {
if (a<b) {
  return a;
} else {
  return b;
}
}

console.log(min(0, 10));

console.log(min(0, -10));
```



2.Define a recursive function isEven corresponding to this description. The function should accept a number parameter and return a Boolean.
```javascript
function isEven(a) {
if (a % 2 === 0){
  return true;
}else if(a % 2 !== 0) {
  return false;
}else {
return
}
}

console.log(isEven(50));

console.log(isEven(75));

console.log(isEven(-1));
```



3.Write a function countBs that takes a string as its only argument and returns a number that indicates how many uppercase “B” characters are in the string.
```javascript
function countBs(){
var bCount = 0
for (var i = 0; i < countBs.length; i++){
  if (countBs[i] == 'B') {
    bCount++;
    return bCount;
  };
}
}

console.log(countBs("BBC"));

```




4.Write a range function that takes two arguments, start and end, and returns an array containing all the numbers from start up to (and including) end.
Next, write a sum function that takes an array of numbers and returns the sum of these numbers. Run the previous program and see whether it does indeed return 55.

```javascript
function range(a, b) {
  var num = []
  for (var i = 0; i <= b; i++) { 
      num.push(i);
  }
  return num;
}

console.log(range(1, 10));
console.log(sum(range(1, 10)));
```


5.The first, reverseArray, takes an array as argument and produces a new array that has the same elements in the inverse order.

```javascript
function reverseArray() {
  var reverse = []
  for(var i = 0; i < reverseArray.length; i++){
   reverse.unshift(i) ;
  }
  return reverse;
}

console.log(reverseArray(["A", "B", "C"]));
```
