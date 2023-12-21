# Basic for loop

Use for Loop to start for  like `for(statement ; condition ; increment)`

```javascript
var i, n = 10;

for (i = 0; i <= n; i++) {
    document.write('<button>Hello ' + i + '</button> </br>');
}

```

**Loop continues**

```javascript

var i, n = 10;

for (i = 0; i <= n; i++) {

    if(i=== 5 || i === 8 ){
        continue;
    }

    document.write('<button>Hello ' + i + '</button> </br>');
}

```

**Loop break**&#x20;

```javascript
var i, n = 10;

for (i = 0; i <= n; i++) {

    if(i=== 5 ){
        break;
    }

    document.write('<button>Hello ' + i + '</button> </br>');
}

```
