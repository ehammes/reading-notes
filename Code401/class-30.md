# Read: 30 -  Hash Tables

## Reading

- [Intro to Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)
- [What is a hash table?](https://www.youtube.com/watch?v=MfhjkfocRR0)
- [Basics of hash tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)
- [Hash table wiki](https://en.wikipedia.org/wiki/Hash_table)

### Notes

#### Terminology

1. **Hash** - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
2. **Buckets** - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
3. **Collisions** - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

#### What are Hashtables

- Hashtables are a data structure that utilize key value pairs. This means every Node or Bucket has both a key, and a value. Since we are able to hash our key and determine the exact location where our value is stored, we can do a lookup in an O(1) time complexity. This is ideal when quick lookups are required.
- Hashing is implemented in two steps:
  - An element is converted into an integer by using a hash function. This element can be used as an index to store the original element, which falls into the hash table.
  - The element is stored in the hash table where it can be quickly retrieved using hashed key.
    `hash = hashfunc(key)
     index = hash % array_size`
- Examples of hashtables:
  - In universities, each student is assigned a unique roll number that can be used to retrieve information about them.
  - In libraries, each book is assigned a unique number that can be used to determine information about the book, such as its exact position in the library or the users it has been issued to etc.

#### Collisions

- A collision occurs when more than one key hashes to the same index in an array. As mentioned earlier, a “perfect hash” will never have any collisions. To put this into perspective, the worst possible hash is one that hashes every single key to the same exact index of an array. The more keys you have hashed to a specific index, the more key/value pair combos you can potentially have.
- A collision is when two different keys resolved to be the same index of the array. The hash map needs to be able to handle two keys resolving to the same index.

#### Internal Methods

- The following methods can be used when working wtih a hastable:
  - `Add()` - adding a new key/value pair to a hashtable
  - `Find()` - finds the key (if exists) and returns the value
  - `Contains()` - accepts a key and returns a boolean if the key exists inside the hashtable
  - `GetHash()` - accepts a key as a string, conducts the hash, and then returns the index of the array where the key/value should be placed.
