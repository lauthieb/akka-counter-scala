# akka-counter-scala

University of Lille, M2MIAGE, CARA project made by Laurent Thiebault & Ludovic Landschoot.

## Objective

Count occurences (words/letters) in a large text file.

## Requirements

* Use Akka actors
* Divide and conquer
  - Use a router actor
  - Send chunks to a worker actor, process them and send the result back
  - Display the result
