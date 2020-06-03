## Object Oriented Programming tutorial using Java and a capstone project.

Here we learn the basics of Object Oriented Programming assuming previous experience in programming in C like languages. We use Java as the language of choice. The tutorial assumes familiarity with syntax though the first chapter gives an overview of the basic syntax in Java.

### CHAPTER 1 : Syntax Cheatsheet
---

#### 1.1 Classes And Objects :
Classes are the encapsulations which contain almost all of the code in a java program. They can be thought of as **blueprints** for creating **objects**.
Before building apartments, we plan the floor design. How big a room should be, how one room connects to the other, what purpose each room serves etc. All this information is stored in a 'blueprint' which can be used to actually build multiple such apartments with same specifications. 
Classes work in a similar way. They store information of the properties of an object (class/instance variables) and it's behavior (methods).

**Objects** are instantiations of a class. Analogous to the brick and mortar apartments built to a specification. They are simply data in the heap memory of the computer. Objects are not directly accessible to the developer. They are interacted with, using a 'reference variable'.
More on this later.

##### Examples :

```java
class Dog {         //class declaration
	int numLegs; 	//class variable (property)
	String name;	//declaration [see 1.2]
}
```

```java
class Test {         
	Dog dog = new Dog();
	//new Dog() creates an instance of the class 
	//Dog and stores it in the heap memory.
	//It's reference is then assigned to a 
	//reference variable dog of data type Dog
}
```


#### 1.2 Variable declaration : 

```
<Type> <name>;
```

##### Examples :
```java
int exampleNumber;
String exampleString;
float exampleFloat;
double exampleDouble;
```

Variables can be declared and assigned a value in the same line. 
'=' is the assignment operator in Java.

```
<Type> <name> = <data of type Type>;
```

##### Examples :
```java
int exampleNumber = 3;
String exampleString = "Hello World!";
float exampleFloat = 3.0f;
double exampleDouble = 3.0;
```

