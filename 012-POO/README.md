# POO

1 hour

POO (Object-oriented programming) allows developers to model software in a very similar fashion to the way we think. In terms of Classes( a category of something), objects (an element inside that category), attributes ( a characteristic of the element), and methods(something the element does). 

# Class:

```Java
public class ClassName {
  // Class body containing attributes and methods
}
```
`public:` This is an access modifier, in this case, making the class accessible from anywhere in the program.
`ClassName:` This is the name you choose for your class, following Java naming conventions (starts with an uppercase letter).
`// Class body:` This is where you define the attributes and methods of the class.

# Object:

```java
ClassName objectName = new ClassName();
```
1. `ClassName:` Replace this with the actual name of your class.
2. `objectName:` This is the name you choose for your object (reference variable).
3. `new ClassName():` This creates a new instance (object) of the ClassName class using the new keyword and the class constructor (which will be discussed later).

# Attribute:

```Java
private dataType attributeName;
```
1. `private:` This is an access modifier, in this case, restricting access to the attribute within the class. Other access modifiers like public and protected are also available.
2. `dataType:` This specifies the data type of the attribute (e.g., int, String, double).
3. `attributeName:` This is your name for your attribute.

# Method:

```Java
public void methodName(dataType parameter) {
  // Method body containing statements
}
```
1. `public:` Similar to the class, this makes the method accessible from anywhere. Other access modifiers exist as well.
2. `void:` This specifies the method's return type. void means it doesn't return any value. Methods can also return other data types.
3. `methodName:` This is the name you choose for your method.
4. `dataType parameter:` This defines an optional parameter the method can receive. Methods can have multiple parameters with different data types.
5. `// Method body:` This is where you write the code the method executes when called.

# Example:

Let's model a new Tesla Model S car with a turn-on engine. 

```Java
public class Car {  // declare class name Car
  private String model;  // with a model Attribute
  
  public void startEngine() {  // And a Start Engine Method
    System.out.println("Engine started!");
  }
}

public class Main {  // Defines the entry point for the program. The execution starts.
  public static void main(String[] args) {  //
    Car myCar = new Car();  // Create object
    myCar.model = "Tesla Model S";  // Set attribute value
    myCar.startEngine();  // Call method
  }
}
```

