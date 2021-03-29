# Functions 

**what is a function?**
function is a set of statments grouped toghether to perform a spicif task. 
we can call them multiple times in more than one place in the code.

> ![func image](https://miro.medium.com/max/700/1*dAwQkc-E0j1AcpdPeGznzg.png)

two ways to declare a function:
1. function expression
```
var msg = 'Sign up to receive our newsletter for 10% off!';
var updateMessage = function () {
var el = document.getElementByld('message'};
el .textContent = msg;
}
updateMessage(); 
```

2. function deceleration
```
function calculateArea(width, height) {
    var area = width * height;
    return area;
}
var first = calculateArea(9,9);
```

> ![func code](https://cdn.programiz.com/sites/tutorial2program/files/javascript-function-with-parameter.png)

