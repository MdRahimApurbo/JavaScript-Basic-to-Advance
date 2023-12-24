# JavaScript Object

This  use calibrates on objects see the example&#x20;

```javascript
var myPc = {
    brand: "corsair",
    screen: "15.6",
    ram: 8,
    ssd: "500GB"
};

document.write(myPc.ram);
```

**For in loop on object**



```javascript
var person = {
    name: "Apurbo",
    age: 25,
    height: "5.6"
}

for (var key in person) {
    document.write(key + ": " + person[key] + "<br>");
}
```
