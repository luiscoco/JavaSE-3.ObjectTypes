# JavaSE-3.ObjectTypes

In Java, everything is an object, and every object belongs to a certain type. 

Types in Java can be broadly categorized into two groups: primitive types and reference types.

## 1. Primitive Types:
These are the most basic data types in Java, and they are not objects. They hold simple values.

### 1.1. int: Represents integer values.

```java
int myNumber = 42;
```

### 1.2. double: Represents floating-point numbers.

```java
double myDouble = 3.14;
```

### 1.3. char: Represents a single character.

```java
char myChar = 'A';
```

### 1.4. boolean: Represents a boolean value (true or false).

```java
boolean myBoolean = true;
```

## 2. Reference Types:

These types include objects, which are instances of classes or interfaces. 

They are stored on the heap and can be more complex than primitive types.

### 2.1. String: Represents a sequence of characters.

```java
String myString = "Hello, Java!";
```

Array: Represents a collection of elements of the same type.

```java
int[] myArray = {1, 2, 3, 4, 5};
```

Class Objects: Instances of user-defined classes.

```java
class Person {
    String name;
    int age;
}

Person person1 = new Person();
person1.name = "John";
person1.age = 25;
```

Interface Types: Instances of interfaces.

```java
interface MyInterface {
    void myMethod();
}

class MyClass implements MyInterface {
    public void myMethod() {
        // Implementation of the method
    }
}

MyInterface myObj = new MyClass();
```

These are just a few examples to give you an idea. In Java, the type system is strong and static, meaning that the type of a variable must be declared at compile time and cannot change during runtime. 

This helps catch errors early in the development process.

