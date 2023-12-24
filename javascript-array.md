# JavaScript Array

On array we use the third bracket see the example

```javascript
var newArr = ["mango", "apple", "banana", "lichu"];

document.write(newArr.join("<br>"));
document.write("<br>"); // Adding an extra line break for clarity
document.write(newArr[2]);

```

**For Loop Over Array**

```javascript
var fruitsArr = ["mango", "apple", "banana", "lichu", "mango"];

for (var i = 0; i < fruitsArr.length; i++) {
    document.write(fruitsArr[i] + "<br>");
}


```

**For in Loop in array**

<pre class="language-javascript"><code class="lang-javascript">
var fruitsArr = ["mango", "apple", "banana", "lichu", "mango"];

for (var fruitItem in fruitsArr ) {
    document.write( fruitsArr[fruitItem] + "&#x3C;br>");
}
<strong>
</strong></code></pre>

**JavaScript Array Concatenation and Array from**

```javascript
// JavaScript Array Concatenation and Array from

// Arrays
var arr1 = [1, 2, 3];
var arr2 = ['A', 'B', 'C'];

// Concatenating arrays
var resultArray = arr1.concat(arr2);
document.write(resultArray + "<br>");

// String
var title = "Hello, My name is Apurbo.";

// Converting string to array using Array.from
var arrTitle = Array.from(title);
document.write(arrTitle);

```

Array Filter Method  we need to use a filter&#x20;



```javascript
var filterArry = [5, 22, 19, 25, 34];

var result = filterArry.filter(function(item){
    
    return item>10;

});

document.write(result);
```

Find array methods filter  this filter only at least of one element values

```javascript
var filterArry = [5, 22, 19, 25, 34];

var findarr = filterArry.find(function(value){
   return value > 15;
});

document.write(findarr);
```

Find index array methods filter  this filter only at least of one element values index number

```javascript
var filterArry = [5, 22, 19, 25, 34];

var findindexarr = filterArry.findIndex((value) => { return value < 10})


document.write(findindexarr);
```

Array ForEach Method



```javascript
var filterArry = [5, 22, 19, 25, 34];

var arrayForeach = filterArry.forEach((value)=>{

    document.write(value + "<br>");

});

```

Array Includes And IndexOf

Include is find array is that include value is available on array and index of is show only the index number

```javascript
var myArry = [5, 22, 19, 25, 34];

var incluidesarray = myArry.includes(25);
document.write(incluidesarray);

var indexofsarray = myArry.indexOf(50);

document.write(indexofsarray);
```

Array Pop Push Reverse

```javascript
var myArry = [5, 22, 19, 25, 34];
var result = myArry.reverse();
document.write(result);
```

```javascript
var myArry = [5, 22, 19, 25, 34];

var result = myArry.push(45);
document.write(myArry);
```

```javascript
var myArry = [5, 22, 19, 25, 34];

var result = myArry.pop();
document.write(myArry);
```

**Array Slice And Sort**

```javascript
var myArry = [5, 22, 19, 25, 34];

var result = myArry.sort();
document.write(result);
```

```javascript
var myArry = [5, 22, 19, 25, 34];

// Slicing the array
var resultSlice = myArry.slice(1, 3);
document.write(resultSlice);
```

Array splice it used select where we want add  or remove element

```javascript
var myArry = [5, 22, 19, 25, 34];

// splice(index,removeCount,item)
//remove 

myArry.splice(1, 2);
document.write(myArry);

//add

myArry.splice(0, 0, 10);
document.write(myArry);

```
