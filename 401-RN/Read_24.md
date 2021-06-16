# Hashtables

> *Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose.* 

> **it is used to determine the index of the array.** 

1. **Buckets:** *A bucket is what is contained in each index of the array of the hashtable.* 

**Each index is a bucket.** 

*An index could potentially contain multiple key/value pairs if a collision occurs.* 

2. **Collisions:** *A collision is what happens when more than one key gets hashed to the same location of the hashtable.*
___
## Structure

- **Hashing**

*Basically, a hash code turns a key into an integer.*

> *their output is determined only by their input.*

 **Hash codes should never have randomness to them.**

>> **The same key should always produce the same hash code.**
___
___
## Creating a Hash

> *A hashtable traditionally is created from an array. After you have created your array of the appropriate size, do some sort of logic to turn that **key** into a **numeric** value.*



1. *Add or multiply all the ASCII values together Multiply it by a prime number such as 599.* 

2. *Divid by the total size of the array.* 

3. *Insert in the array at that index.*

4. *The idea is to store the key into this data structure, and quickly retrieve the value.* 

5. *Encode the key that will eventually map to a specific location in the data structure that we can look at directly to retrieve the value.*


6. *Lookup in an O(1) time complexity. This is ideal when quick lookups are required.*



