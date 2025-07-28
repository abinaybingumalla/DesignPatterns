# Structural Design Patterns (5)

## Factory Design Pattern

Define and interface and let subclasses decide which class to instantiate

### Usage

+ When a class does not know what subclass to create
+ When a class want the subclasses to specify the object to be created.
+ When parent class take care of creating the objects of your subclasses

## Singleton
Class ensures that it has only one single instance created
  + Early instantiation
  + Lazt instantiation

### Usage
+ In multi threading or databse applications
+ Used in log4j (one instance of logger class)
+ Caching, threadpools & configurations

## Builder
Used to construct a complex object from simple objects with a step by step process
Mostly used when your object cannot be created in a single step
