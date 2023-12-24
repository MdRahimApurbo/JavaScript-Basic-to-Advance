# JavaScript String Methods

```javascript
var myString = "hello everybody";
var myName = "My name is Apurbo";

var resultCharAt = myString.charAt(4);
var resultConcat = myString.concat(myName);
var resultIndexOfH = myString.indexOf("h");
var resultLastIndexOfL = myString.lastIndexOf("l");
var resultReplace = myName.replace("Apurbo", "John"); // Replace "Apurbo" with the desired replacement
var resultSubstr = myName.substr(11, 6); // Start at index 11 and extract 6 characters

document.write("Original String: " + myString + "<br>");
document.write("charAt(4): " + resultCharAt + "<br>");
document.write("indexOf('h'): " + resultIndexOfH + "<br>");
document.write("lastIndexOf('l'): " + resultLastIndexOfL + "<br>");
document.write("Replace 'Apurbo' with 'John': " + resultReplace + "<br>");
document.write("substr(11, 6): " + resultSubstr + "<br>");

// Additional string methods
document.write("Uppercase: " + myString.toUpperCase() + "<br>");
document.write("Lowercase: " + myName.toLowerCase() + "<br>");
document.write("Substring(6, 11): " + myName.substring(6, 11) + "<br>");
document.write("Split(' '): " + myString.split(' ') + "<br>");

```
