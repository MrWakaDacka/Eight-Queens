# EightQueens 

EightQueens problem solution in java with brute force, hill climbing and simulated annealing.

### Example

```java
$ java BenchmarkTest bruteforce hillclimbing simulatedannealing
Benchmarking brute force...
Total time elapsed: 0.098
Total try(restart) count: 253002
Solution: 
| X |   |   |   |   |   |   |   |
---------------------------------
|   |   |   |   |   | X |   |   |
---------------------------------
|   |   |   |   |   |   |   | X |
---------------------------------
|   |   | X |   |   |   |   |   |
---------------------------------
|   |   |   |   |   |   | X |   |
---------------------------------
|   |   |   | X |   |   |   |   |
---------------------------------
|   | X |   |   |   |   |   |   |
---------------------------------
|   |   |   |   | X |   |   |   |
---------------------------------

Benchmarking hill climbing...
Total time elapsed: 0.006
Total step count: 108
Total try(restart) count: 33
Solution: 
|   |   |   |   |   | X |   |   |
---------------------------------
|   |   | X |   |   |   |   |   |
---------------------------------
| X |   |   |   |   |   |   |   |
---------------------------------
|   |   |   |   |   |   |   | X |
---------------------------------
|   |   |   | X |   |   |   |   |
---------------------------------
|   | X |   |   |   |   |   |   |
---------------------------------
|   |   |   |   |   |   | X |   |
---------------------------------
|   |   |   |   | X |   |   |   |
---------------------------------

Benchmarking simulated annealing...
Total time elapsed: 0.007
Total step count: 303
Total try(restart) count: 1
Solution: 
|   |   |   |   | X |   |   |   |
---------------------------------
|   |   |   |   |   |   | X |   |
---------------------------------
|   | X |   |   |   |   |   |   |
---------------------------------
|   |   |   |   |   | X |   |   |
---------------------------------
|   |   | X |   |   |   |   |   |
---------------------------------
| X |   |   |   |   |   |   |   |
---------------------------------
|   |   |   | X |   |   |   |   |
---------------------------------
|   |   |   |   |   |   |   | X |
---------------------------------

```
