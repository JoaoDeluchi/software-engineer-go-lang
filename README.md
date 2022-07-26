# software-engineer-go-lang

## Solid 

### Single Responsability 

#### In any well-designed system, objects should only have a single responsability - Uncle Bob


### Open/Closed principle 

#### A software module should be open for extension but closed for modification - Bertrand Meyer 

### Liskov substitution 

#### If, for each object, O1 of type S there is an object O2 of type T such that for all programs P defined in terms of T, the behavior of P is unchanged when O1 is substituted for O2, then S is a subtype of T. - Barbara Liskov

### Interface Segregation 

#### Clients should not be forced to depend upon the interfaces that they do not use. - Uncle Bob

### Dependency Inversion 

#### High-level  modules should not depend on low level modules. Both should depend on abstractions. abstractions should not depend on details. Details should depend on abstractions. - Uncle Bob(AGAIN)

## Golang Proverbs

### The application of the SOLID principles works as a guide for splitting our code into amaller packages where each package implements a Specific bit of functionality and its interfaces serve as the glue for wiring packages together when building larger systems

### A little copy is better than a little dependency

### Concurrency is not parallelism 

### Clear is better than clever 

### Errors are values 

### Doc is for users 

## Variable naming Conventions 

#### Two approaches:
##### - clear and self-descriptive names 

##### - short and minimalist names 

#### look how the name will affect the engineers who share the same code base with you

## Accept interfaces, Return structs - Jack lindamood


PAGE 60
