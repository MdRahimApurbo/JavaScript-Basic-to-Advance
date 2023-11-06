# Inner Function in Javascript

Nexted  Function

```

function something (great, name){

    function sayHi (){
    
        console.log(great, name)

    }

    sayHi()

}

something('Good Morning', 'Apurbo')

```

Another Example

````
```javascript
function something (great, name){

    function fisrtName (){
    
        if(name){

            return name.split(' ')[0]

        }

    }

    var message = great + ' ' + fisrtName()

    console.log(message);

}

something('Good Morning', 'Rahim Apurbo')
```
````
