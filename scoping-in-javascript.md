# Scoping in Javascript

Inner function and scoping Example

```
function testNumber(arr){

    function a(){
        return arr%3 === 0
    }

    function b(){
        return arr%5 === 0
    }

    if(a() && b()){

        console.log(arr + ' is divided by 3 and 5')

    }else{

        console.log(arr + ' is not divided by 3 and 5')

    }
    
}

testNumber(15)
```
