---
layout: page
title: System Design Crash Course
categories: software
---

##### Core Concepts
###### Vertical vs Horizontal Scaling
 * Vertical Scaling: Adding more CPU, Memory, Network bandwidth, etc.
 * Horizontal Scaling: Add more hosts or nodes

###### CAP Theorem
 * C (Consistency) A (Availability) P (Partition Tolerance)
 * Consistency - When you read, you have the most recent write
 * Availability - Your system remains available through failures
 * Partition Tolerance - You system can survive a network partition
