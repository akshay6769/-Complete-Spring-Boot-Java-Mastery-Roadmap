# 👨‍🏫 OOP Concepts in Java

## 🔸 1. Inheritance
Allows a class to inherit fields and methods from another.

```java
class Animal {
   void sound() { System.out.println("Animal sound"); }
}

class Dog extends Animal {
   void bark() { System.out.println("Dog barks"); }
}
