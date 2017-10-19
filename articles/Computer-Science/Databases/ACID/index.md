---
title: Acid
---

## Acid

ACID stands for Atomicity, Consistency, Isolation, Durability. It is a set of properties of database transactions intended to guarantee validity even in the event of errors, power failures, etc.

Atomicity: Each transaction is "all or nothing". Either executes succesfully or aborts. No partial executions.
Consistency: A transaction takes the database from one valid state to another.
Isolation: Subsequent transactions on a database are excecuted independently of each other.
Durability: Once a transaction has been committed, it will remain so, even in the event of power loss, crashes, or errors. 

