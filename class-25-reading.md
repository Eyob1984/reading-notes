# Reading-Notes

                        ** Class-25 - Hash Tables**
                        
                        
#### Is a HashTable useful for search or sorting operations? Why?

 * No, A Hashtable has no predictable iteration order, and cannot be sorted.

#### What makes a good hash function?

* There are four main characteristics of a good hash function:

  1. The hash value is fully determined by the data being hashed.
  
    * If something else besides the input data is used to determine the hash, then the hash value is not as dependent upon the input data, thus allowing for a worse distribution of the hash values.
  
  2. The hash function uses all the input data.
  
    * If the hash function doesn't use all the input data, then slight variations to the input data would cause an inappropriate number of similar hash values resulting in too many collisions
  
  3. The hash function "uniformly" distributes the data across the entire set of possible hash values.
  
    * If the hash function does not uniformly distribute the data across the entire set of possible hash values, a large number of collisions will result, cutting down on the efficiency of the hash table
  
  4. The hash function generates very different hash values for similar strings.
  
    * In real world applications, many data sets contain very similar data elements. We would like these data elements to still be distributable over a hash table.
    
   [Reference](https://www.sparknotes.com/cs/searching/hashtables/section2/)

#### Why should you try to reduce the number of collisions?

* If we have more collisions the data could be lost as two different keys begin to overwrite each ohter at their position on the array.

#### What is stored at each index of a HashTable? Why?

*



[home](https://eyob1984.github.io/reading-notes/)
