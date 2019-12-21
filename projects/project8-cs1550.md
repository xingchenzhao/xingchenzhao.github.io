---
layout: project
type: project
image: images/operatingsystem2.png
title: CS1550 INTRODUCTION TO OPERATING SYSTEMS Projects (University Course)
permalink: projects/cs1550
# All dates must be YYYY-MM-DD format!
date: 2019-04-30
labels:
  - C
  - Operating System
summary: CS1550 INTRODUCTION TO OPERATING SYSTEMS Projects  (University of Pittsburgh)
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/operatingsystem2.png">
</div>

# CS1550 INTRODUCTION TO OPERATING SYSTEMS Projects  (University of Pittsburgh)

https://github.com/xingchenzhao/CS1550

## Course Outline

**Goal:**
An introduction to basic concepts of operating systems, common to most computer systems, which interfaces the machine with upper-level programs. This course will introduce processes as processing unit, process management, concurrency, communication, memory management and protection, and file systems.
## Projects

# Project1
Anytime we share data between two or more processes or threads, we run the risk of having a race condition where our data could become corrupted. In order to avoid these situations, we have discussed various mechanisms to ensure that one program’s critical regions are guarded from another’s.
# Project2
Anytime we share data between two or more processes or threads, we run the risk of having a race condition where our data could become corrupted. In order to avoid these situations, we have discussed various mechanisms to ensure that one process’ critical regions are guarded from another’s.
One place that we might use parallelism is to simulate real-world situations that involve multiple independently acting entities, such as people. In this project, you will use condition variables and locks to simulate the safe apartment inspection problem
# Project3
In class, we have been discussing various page replacement algorithms that an Operating System implementer may choose to use. In this project, you will compare the results of three different algorithms on traces of memory references. While simulating an algorithm, you will collect statistics about its performance such as the number of page faults that occur and the number of dirty frames that had to be written back to disk. When you are done with your program, you will write up your results and provide a graph that compares the performance of the various algorithms.
The three algorithms for this project are:
* Opt – Simulate what the optimal page replacement algorithm would choose if it had perfect knowledge
* FIFO – Implement first-in, first-out
* Aging – Implement the aging algorithm that approximates LRU with an 8-bit counter. Do a refresh of the R bits every P CPU cycles.

