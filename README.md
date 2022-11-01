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

![image](https://user-images.githubusercontent.com/110039102/199209203-11669505-7409-4206-977b-6e83d2bc58b4.png)

To minimalise coupling among modules:

- Subroutines or modules should only be allowed to access that data which they need to perform their assigned task
- All data transfer between modules is visible in the module parameters
- There must be no hidden flows of data via global variables or shared data areas
- There should be no control information passing between modules, e.g Boolean flags
- The number of module parameters should be minimal

![image](https://user-images.githubusercontent.com/110039102/199210515-c25a2e0b-f6c3-49f2-a185-70896b2345d8.png)

### Stepwise refinement

The focus of structured design is the identification of components of the system and how they interact, i.e the software architecture of the computerised system, and not on the internal design of the components.

For the **internal design of the components**, i.e the program source code for subroutines and the program which calls these subroutines, we use structured programming.

https://www.youtube.com/watch?v=jfQcKLKvjeQ

Stepwise refinement starts with the **major steps**.

Each major step is then refined into a **more detailed sequence of steps**.

Each one of these more detailed steps is then refined and so on until a stage is reached where the steps can be replaced by programming language statements,

[Problem solving Worksheet 2 Structured programming.pdf](https://github.com/Minwauu/Structured-Design/files/9908945/Problem.solving.Worksheet.2.Structured.programming.pdf)







