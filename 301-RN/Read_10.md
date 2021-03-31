# Call stack 

> - A stackfunction is a function that contains multuiple functions call-back so it would look like a chain calling the main function will call all other functions inside of it.

> - if the call back function took more space it will results a  `stack overflow` error. 

![img](https://miro.medium.com/max/638/1*CCHexfHNCNo-f8aw3rbRew.jpeg)

## Why It's Necessary
> - we mostly use it to execute asynchronous codes. 

```
function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();
```

## What is a StackOverFlow

> - it occurs when a function calls itself without break point.

# Error messages

![img](https://reactjs.org/static/f1276837b03821b43358d44c14072945/c3a47/error-boundaries-stack-trace.png)

## Major error Types

1. Reference errors: for not declared vars.
2. Syntax errors: for typos.
3. Range eroors: if arrays of any type had an our of rage length.
4. Type errors: its variables type related (String, int, bool, etc).

and a lot more on [JavaScript error reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)

## Debugging 
> - its used to check the running code line by line to get where exactly an error happens. 


## Handling errors 
> - when arrors are found you can solve theme easly, but what if you didnt know if there are errors would appear on the long term. 
**you can handle any unexpected error using a TRY CATCH.**
> - write a TRY for the normal code you want and a CATCH to return an error message at least in case of errors. 


## Tools to avoid runtime errors 
1. quokka: to evaluate the code. 
2. eslint: consistance style guide.
3. TypeScript: recommanded for strong script proggrammers. 