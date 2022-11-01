# Structured-Design

### Quickfire Five

**What is the difference between an indefinite and a definite iteration?** - Definite is where the amount of loops can be predicted or is known beforehand whereas with indefinite it is unknown and continues until a condition is met.

**Which sequence is generated by this recurrence relation?** - The Fibonacci sequence.     

![image](https://user-images.githubusercontent.com/110039102/199202315-f8664961-2740-4672-b388-275dd3a68b91.png)

**Why is understanding stack frames relevant to understanding the usefulness of recursion?** - Stack frames generate every time there is a recursive call which takes up memory and time.

**What is a datum? Give some examples of how a datum could be interpreted.** - A singular piece of data, represented by a series of bits. E.g characters

## Programming paradigms and structured design
![image](https://user-images.githubusercontent.com/110039102/199205566-66a74dfa-3154-4631-938e-bd37c50b07ba.png)
- A paradigm is a standard, perspective, or set of ideas.
- To design is to plan or mark out the form and method of solution. 


Structured design is a disciplined process of deciding which components interconnected in which way will solve some well-specified problem. 

A problem is divided into smaller and smaller sub problems, so that each sub problem will eventually correspond to a component of the system which solves the problem. 

The partitioning process into smaller and smaller sub problems is done until the sub problems are:

- manageably small and
- solveable separately i.e relatively independent of one another

A **good** design is an exercise in partitioning and organising the pieces of the system so that each is **cohesive** and **loosely coupled**. (The pieces of the system are referred to as **modules** or **units** or **components** and can be implemented with subroutines.

### Cohesion

**Cohesion** measures the strength of the interconnection between elements within a module. To achieve cohesion, highly interrelated parts of the real-world problem should be in the same piece of the software system, i.e things that belong together should go together.

![image](https://user-images.githubusercontent.com/110039102/199208605-443598aa-9204-4700-bea9-1ccb100f0bda.png)

### Loosely coupled




