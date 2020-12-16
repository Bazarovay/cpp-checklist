# Design Document Template

A generic design document template for systems.

# Title

## Problem Statement

*What is the goal of the service? What is the problem statement?*
*Also add what is in scope for the review*

## In scope/Out of scope

## Requirements:
*Product features, user requirements*

## Non-Functional Requirements | Use actual numbers instead of generic terms:
*Product properties, user expection*
Examples:
- High Availability, Low Latency, Concurrent, Authenticated, Encrypted, Multi-Tenant etc
- Works even when low network bandwidth
- Maintainability, evolvability, reusability

## Back of Envelope Estimations
- Memory
- I/O
- Storage
- Network Usage

## Assumptions | Each assumption should have a reason why it is valid.

## Potential Solutions
---------------------------------------------------------------------------------------------------
### Solution 1

##### Comments:
- Any assumptions
- Change in estimation

##### Pros
- more maintainable, etc

##### Cons
- Limitations, high learning curve, complexity, engineering effort, etc

##### Task Breakdown
Tasks and rough estimates to understand the engineering effort

#### System Design and Architecture 
Think about the requirement, actors, and use cases. KISS, YAGNI, SOLID.

##### Data Flow
- How the data flows through the system

##### Sequence Flow

##### Process Flow

### Glossary


---------------------------------------------------------------------------------------------------
## Suggested Solution

---------------------------------------------------------------------------------------------------


### Dependencies
- Hard
- Soft

### Service Level Objects


### Fault-Tolerance
- What errors can occur
- How to recover

## Test Plan

* How can the design be tested

## References/Resources 
- References, links to additional documentation
