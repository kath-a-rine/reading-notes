# Hash Tables

**What is a hash table?**

A hash table is a data structure used to store information. It's information has keys and values. It's a way to implement an *associative array*.

**What is an associative array?**

An array that uses named keys assigned to them. 

**What is a hash function?**

A hash function takes in a key value and returns an integer (the index) number pointing to the location of the associated value.

## Terminology

*Hash* - the result of an algorithm taking a string and converting it to a value that could be used for security or some other purpose. *A hash is the ability to encode the key that will eventually map to a specific location in the data structure that we can look at directly to retrieve the value.*

*Buckets* - what is contained in each index of the array of the hash table.

*Collisions* - occur when more than one key hashes to the same index of an array. A *perfect hash* will never have any collisions.

- collisions are solved by changing the initial state of the buckets. Rather than start at `null`, a `LinkedList` can be initialized and each key/value pair can be stored as a node within that linked list.

***Hash maps store values by:***

- accepting a key
- calculating the hash of the key
- use modulus to convert the hash into an array index number
- store the key with the value byt appending both to the end of a linked list

***Hash maps read values by:***

- accepting a key
- calculating the hash of the key
- use modulus to convert the hash into an array index number
- use that array index to access the linked list representing a bucket
- search through the bucket for a node with the key/value pair matching the key given

### Internal Methods

`Add()`

When adding a new key/value pair to a hashtable:

- send the key to the `GetHash` method.
- Once you know the index of where it should be placed, go to that index
- See if something exists at that index already, if not, add it with the key/value pair.
- If something does exist, add the new key/value pair to the data structure within that bucket.

`Find()` - takes in a key, gets the Hash, and goes to the index location.

`Contains()` - accepts a key and returns a boolean on if that key exists within the table.

`GetHash()` - accepts a key as a sting, conducts the hash, and returns the index of the array where the key/value should live.