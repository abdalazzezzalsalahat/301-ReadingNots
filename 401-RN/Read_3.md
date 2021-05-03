# Files in python


#### what is a file
> A set of bytes that we use to store data.

**Contains:**
        *1. Header*
        *2. Data*
        *3. End*

#### File paths 
> **Its is mainly the folder(directory) path and the file name with it's extention.**

#### Line endings
**File lines ends with *`\r\n`* CR + LF.**


#### Opening and closing file in Python
- *We write **`file = open(example.extention)`** to open a file.*

- *We write **`file.code()`** to close the file.*
- *We write **`with open(example.extention) as reader:`** as a second way to close a file.*


to strict the use of a file we use:
1. `r`: its the default and only for reading
2. `w`: for writeing, updating, delete a files data.
3. `rb`|`wb`: to open a file in binary mode.

> It would look like this **`file = open(example.extention, 'r')`**.

**RAW Files would look like this `open(example.extention, 'r', buffering=0)`**


#### Reading and Writing in files
**- we use `file.read(size=-1)` but it reads a file in bytes with the size givin but in case of `-1` it means the whole file.**

**- we use `file.readline(size=-1)` but it reads a spicific columns in a line but in case of `-1` it means the whole line.**

**- we use `file.readlines()` it reads all lines as a list.**

**- we use `file.write('string')` it writes a string in a file.**

**- we use `file.writelines(seq)` it writes multilines in a file.**

**To looping over lines write:**
```
with open(example.extention) as reader:
    line = reader.readline()
    while line != '' : 
        print(line, end='')
        line = reader.readline()
```
**OR**
```
with open(example.extention) as reader:
    for line in reader.readlines():
        print(line, end='')
```

*PNG in ASCII ==> **0x50 0x4E 0x47***


> ***Use* __file__ *attribute for more dinamic results.***

- `a`: to append a populated file

**If we want to include mor that one file we assign a *variable* for each file and continue.**

#### Python files libraries

1. `wave`: *for WAV audio files.*
2. `aifc`: *AIFF, AIFC audio files.*
3. `sunau`: *for SUN AU files.*
4. `tarfile`: *for TAR archives.*
5. `zipfile`: *for ZIP archives.*
6. `configparser`: *to create a parse configuration files*
7. `xml.etree.ElementTree`: *for XML files*
7. `msilib`: *for Microsoft installer files*
8. `plistlib`: *Mac OSX files*
9. `PyPDF2`: *PDF toolkit*
9. `xlwings`: *for Excel files*
9. `Pillow`: *image reading and manipulation*

# Exceptions in Python


**Exceptions versus Syntax Errors**
> **Syntax** accurs for incorrect statments.
> **Exceptions** accurs if code results an error.


**The AssertionError Exception**
> *It happins if the condition was false.*

`assert expected == actual`


**The try and except Block: Handling Exceptions**
> *We use it to catch and handle exceptions.*
```
try:
    function()
except: 
    print('error')

```
*catching exceptions hides all errors.*

**The else Clause**
> *The `else` will be executed only when there is no exceptions.*

```
try:
    linux_interaction()
except AssertionError as error:
    print(error)
else:
    print('Executing the else clause.')

```

**Cleaning Up After Using finally**
> *It runs always with or without axceptions.*
```
try:
    #do somthing
except:
    #do somthing
else:
    try:
        #do somthing
    except:
        #do somthing
finally:
    #do somthing
```

