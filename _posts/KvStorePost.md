---
title: A try at making a CHORD implementation with redundancy
date: 2022-12-23 12:00:00 -500
categories: [school project,cloudcomputing]
tags: [p2p,CHORD,python,Key-Value store,distributed database]
---

# A try at making a CHORD implementation with redundancy

I had a course in which we add to design, implement and benchmark a Cloud system. With my team, we decided to make a proof of concept of redundancy over a CHORD system. Unfortunately, this didn't go well, as we will see.

### Table of Content
* I. Introduction
    * I.1 What is Chord ?
    * I.2 What is GRPC ?


## I. Introduction
### What is Chord ?
A HashTable is an abstract data type that maps keys and their associated value into buckets. The main principle here is that a function is applied when a key-value couple is registered into the hashTable. 
The hash function assign to each key a unique bucket, and the value coupled with the key is stored in that bucket.
Later, when a request is made to the hashTable against the key, the correspondant value can be found in the bucket pointed by the hash of the said key.

So the hash function  


