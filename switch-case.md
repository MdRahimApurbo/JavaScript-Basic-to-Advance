# Switch Case

**This else-if statement same work we can execute on the switch statement**

```javascript
var mark = 10;


switch (true) {
    case (mark >= 80 && mark <= 100):
        document.write('Yot get A+');
        break;
    case (mark >= 70 && mark <= 79):
        document.write('Yot get A');
        break;
    case (mark >= 60 && mark <= 69):
        document.write('Yot get A-');
        break;
    case (mark >= 50 && mark <= 59):
        document.write('Yot get B');
        break;
    case (mark >= 40 && mark <= 49):
        document.write('Yot get C');
        break;
    case (mark >= 33 && mark <= 39):
        document.write('Yot get D');
        break;
    default:
        document.write('You get Fail')
        break;
}
```
