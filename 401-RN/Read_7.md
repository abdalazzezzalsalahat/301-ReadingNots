# Python Scope & the LEGB Rule: Resolving Names in Your Code


**What LEGB stands for? **
> *Local, Enclosing, Global, and Built-in*

> *Scope of a name defines the area of a program in which you can unambiguously access that name, such as **variables**, **functions**, **objects**.*

# Scops:

#### Global scope:
> *They are available to all the code.*

#### Local scope: 
> *They are only available to the code within the scope.*

## Names and Scopes in Python

> *Variables in Python come into existence when you first assign them a value, because python is a dynamic language.*


## Namespace

> *Namespaces are good python mechanisms to store variables and we call it using `__dict__` spicial attribute.*


## Using the LEGB Rule for Python Scope

#### Functions (Local Scope)

> *Local scope and we use them every time we call a function.*

#### Nested Functions

> *It only exists for neasted functions, it contains all the variables and the functions created inside it.*


#### Modules (Global Scope)

> *It contains all the variables, local functions and global functions that are called or created or called inside it.*

#### Built-ins

> *They are created when we open an interactive session or run a script.*