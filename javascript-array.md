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

Array Filter Method  we need use filter&#x20;



```javascript
var filterArry = [5, 22, 19, 25, 34];

var result = filterArry.filter(function(item){
    
    return item>10;

});

document.write(result);
```
