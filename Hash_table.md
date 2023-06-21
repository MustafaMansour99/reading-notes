# Hashing is a technique that is used to uniquely identify a specific object from a group of similar objects. Some examples of how hashing is used in our lives include:

- In universities, each student is assigned a unique roll number that can be used to retrieve information about them.
- In libraries, each book is assigned a unique number that can be used to determine information about the book, such as its exact position in the library or the users it has been issued to etc.

In both these examples the students and books were hashed to a unique number.

---

## Hashing is implemented in two steps:

1. An element is converted into an integer by using a hash function. This element can be used as an index to store the original element, which falls into the hash table.

2. The element is stored in the hash table where it can be quickly retrieved using hashed key.
hash = hashfunc(key)
index = hash % array_size

## Hash function

A hash function is any function that can be used to map a data set of an arbitrary size to a data set of a fixed size, which falls into the hash table. The values returned by a hash function are called hash values, hash codes, hash sums, or simply hashes.

---

## To achieve a good hashing mechanism, It is important to have a good hash function with the following basic requirements:

1. ***Easy to compute: It should be easy to compute and must not become an algorithm in itself.***

2. ***Uniform distribution: It should provide a uniform distribution across the hash table and should not result in clustering.***

3. ***Less collisions: Collisions occur when pairs of elements are mapped to the same hash value. These should be avoided.***
