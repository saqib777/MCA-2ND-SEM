MCA 2nd SEM - OPPS with Java - Important Questions

5 Marks 
1. What are Variables??  



### Q2. Define OOPs concept in Java

**Answer:**

OOPs (Object-Oriented Programming System) in Java is a programming paradigm based on the concept of **objects** that contain data and methods. It helps in organizing software design around data, or objects, rather than functions and logic.  

The main **principles of OOPs** in Java are:  

1. **Encapsulation:**  
   Wrapping data (variables) and methods (functions) together into a single unit called a class. It hides the internal details and provides controlled access using getters and setters.

2. **Inheritance:**  
   The process by which one class (child or subclass) can acquire the properties and behaviors of another class (parent or superclass). It promotes code reuse.

3. **Polymorphism:**  
   The ability of a single function, method, or operator to behave differently based on context. In Java, it is achieved through method overloading and method overriding.

4. **Abstraction:**  
   Hiding complex implementation details and showing only the necessary features of an object. It is achieved using **abstract classes** and **interfaces**.

**In short:**  
OOPs in Java enables modular, reusable, and maintainable code by modeling real-world entities as objects.

### Q3. What are Arrays?

**Answer:**
An **array** in Java is a **data structure** that allows storing multiple elements of the **same data type** in a single variable.  
Instead of declaring multiple variables for each element, an array stores all elements in a **contiguous memory location** and provides **indexed access**, where the first element starts at index 0.  

Arrays can be:
- **Single-dimensional:** A simple list of elements (e.g., `int[] numbers = {1, 2, 3};`)
- **Multi-dimensional:** Arrays of arrays, like matrices (e.g., `int[][] matrix = new int[3][3];`)

Arrays are efficient for **iterating, sorting, and managing data collections** of fixed size.  
However, their size cannot be changed once created, which is why dynamic structures like **ArrayList** are often used.  

---

### Q4. Define an Exception

**Answer:**
An **exception** in Java is an **event or error** that occurs during the execution of a program, interrupting its normal flow.  
Java provides a robust **exception-handling mechanism** to manage runtime errors, allowing the program to continue instead of crashing.  

Exceptions are objects derived from the `Throwable` class and are categorized into:
- **Checked Exceptions:** Checked at compile time (e.g., `IOException`, `SQLException`).
- **Unchecked Exceptions:** Occur at runtime (e.g., `NullPointerException`, `ArithmeticException`).

Java handles exceptions using **try**, **catch**, **throw**, **throws**, and **finally** blocks.  
This helps in writing **secure, reliable, and maintainable** programs by managing unexpected situations gracefully.

---

### Q5. What is Pluggable Look and Feel?

**Answer:**
The **Pluggable Look and Feel (PLAF)** in Java allows Swing applications to **change their graphical appearance** dynamically without altering the program’s logic.  
It provides a mechanism to separate the **user interface design** from the **application functionality**.  

Java Swing supports multiple built-in look and feels such as:
- **Metal** (default Java look)
- **Nimbus**
- **Windows**
- **Motif**

Developers can also create **custom look and feel** classes.  
It is implemented using the `UIManager.setLookAndFeel()` method, allowing applications to appear **native to the operating system** or maintain a consistent look across platforms.  

Example:  
```java
UIManager.setLookAndFeel("javax.swing.plaf.nimbus.NimbusLookAndFeel");
```

---

### Q6. Name the various Input Streams available in Java.

**Answer:**
Java provides the **InputStream** class as the **base class** for all byte-oriented input operations.  
Input streams are used to **read data** from various sources such as files, memory, or network connections, **one byte at a time**.  

Some important types of Input Streams are:

1. **FileInputStream:** Used to read data from files on the disk.  
2. **ByteArrayInputStream:** Reads data from an array of bytes in memory.  
3. **BufferedInputStream:** Adds buffering to input streams for efficient reading of large data.  
4. **DataInputStream:** Allows reading Java primitive data types (int, double, etc.) from an input stream.  
5. **ObjectInputStream:** Used to read objects that were previously serialized and saved to a stream.  
6. **PipedInputStream:** Connects with a `PipedOutputStream` to allow inter-thread communication.

Together, these classes form a powerful system for **handling input in different forms**, providing flexibility and performance.





