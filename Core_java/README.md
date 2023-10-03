# Java_Fundamentals
## 23. JDK JRE JVM
- JDK: Java Dvelopment Kit is a tool that using compile the java code to byte code
- JVM: Java Virtual Machine that means you have to run the code on it
- JRE: Java Runtime Environment

## Static
#### [Static variables](https://github.com/markdown-it/markdown-it-emoji) 
Static variables is shared by all the object. If yuo want to refer a static variable, you can use a class name. Eg. ClassName.variableStatic
#### [Static method](https://github.com/markdown-it/markdown-it-emoji) 
- Using it: ClassName.method();
- Using static variable inside static method
- If not using static method for main, deadlock occur because you need to create object for main, and the main is the start point for execution.
#### [static block](https://github.com/markdown-it/markdown-it-emoji) 
```java
static String name;
static
{
   name = "Create Name";
}
```
- Whenever creating the object, the static block will be invoked firstly
- If you don't create a object, you can use it code to call static block (It's means that class load)
```java
Class.forName(className:"className");
```
## 54. Access Modifiers

## 56. Dynamic Method Dispatch

## 57. Final keyword

## 58. Object Class equals toString hashcode

## 59. Upcasting and Downcasting

## 60. Wrapper Class

## Exception

## Thread

## 96. Collection API

## Container



