
# logical operators 

` &&,  ||,  ! `
'AND,  OR,  NOT'

> According to the truth table as shown below 

## Truth table 
![Truth table](https://www.realdigital.org/img/228d4788d26e286b5706f6d644ddee8b.svg)

**the resault of any logical operator will only be either 'True' or 'False'**


# Loops 

> Loops check a condition, if it returns true the loops will run until the 
> Condition returns fals.
> There are three types of loops, but they all work almost the same.


![loops image](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code/loop_js-02-farm.png)



- `for` 
- `while`
- `do while`

```
/*the for loop*/
for (var i = 0; i < 10; i++){
    //what to do if it was true
}
/////////////////////////////
```
```
/*the while loop*/
var i = 0;
var variables = /*any varialbe inside the condetion*/

while (i < 10){
    //what to do if it was true
    i++;
}
/////////////////////////////
```
```
/*the do while*/
do {
    //what to do if it was true
    i++;
}while (i < 10);

```

Each loop initialize at some value, here we have them all as **(i)** 
it will act as a *counter* to reach a *specific* value in a *specific* way,
based on the condition which it can be anylogical comparasion and the update 
which also could be in any value by adding a value to our initializer *i*
