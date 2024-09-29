# CompSt 751 Group Project

## Name
SprayList implementation in Java

## People
 1) Vijaya Nishitha Vattem, vvattem@uwm.edu
 2) Kavya Sri Mudunuri, kavyasri@uwm.edu
 3) Sravani Sugasani, sugasani@uwm.edu
 4) Godha Nukala, gnukala@uwm.edu

## Introduction
The SprayList is a scalable relaxed priority queue designed to efficiently handle concurrent operations in multi-threaded environments. It relaxes the strict ordering of elements typically required in priority queues, which helps improve performance and scalability. By distributing access and limiting contention between threads, the SprayList provides fast insertion and deletion of elements while maintaining an approximate priority order, making it ideal for large-scale systems where performance and throughput are key.

## Scope
We will be implementing the Spraylist data structure as described in the paper and test its various mentioned use-cases along with assessing its pros and cons with standard data structures. We will also formulate the spraylist validation cases and do invariant checks for structural sanity.
Further efficiency tests will be made to test its efficient searching and querying as suggested in the paper

## Paper
https://dl.acm.org/doi/pdf/10.1145/2688500.2688523





