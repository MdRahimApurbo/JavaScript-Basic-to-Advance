# First Class Function



```javascript
first Class Function
```

```javascript
function add(a,b){

    return a+b

}
```

```javascript
variable function
```

```
var sum = add

console.log(sum(4,5))
```

```javascript
function stored in a array
```

```javascript
var arr = []

arr.push(add)
console.log(arr)
console.log(arr[0](5,3))
```

```javascript
function stored in a Object
```

```javascript
var obj = {
    sum:add
}

console.log(obj);
console.log(obj.sum(7,9));
```

<pre class="language-javascript"><code class="lang-javascript"><strong>Function Created As Need
</strong></code></pre>

```javascript
setTimeout(function(){
    console.log('I Have Created ...')
}, 1000)
```
