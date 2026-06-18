# Day 02 Notes - Java Developer Journey

* Declare and use variables.
* Understand Java data type.
* Take user input using Scanner.
* Create simple employee-related programs.

---

## Variable?

### What is a Variable?
* A variable is a container that store data.
```base
String name = "Suvendu";
int age  = 25;
double salary = 50000.50;
```
* int -> Data type
* name -> Variable name
* Suvendu -> Value

## Java Data Types
* Java has two categories:
1. Primitive Data Type

|Type                   | Size                 |
| --------------------- | -------------------- |
| byte                  | 1 byte (100)         |
| short                 | 2 bytes (20000)      |
| int                   | 4 bytes  (100000)    |
| long                  | 8 bytes (99999999)   |
| float                 | 4 byte (10.5f)       |
| double                | 8 byte (10.5678)     |
| char                  | 2 byte ( 'A' )       |
| boolean               | 1bit (true/false)    |

### Example Program
```
public class DataType {
    public static void main(String[] args){
        int age = 25; // Integer data type
        double salary = 1000.50; // Double data type
        char grade = 'A'; // Character data type
        boolean isEmployed = true; // Boolean data type

        System.out.println("Age: " + age);
        System.out.println("Salary: " + salary);
        System.out.println("Grade: " + grade);
        System.out.println("Is Employed: " + isEmployed);

    }
}
```
* Output
```
D:\Java-Journey\Week-01\Day-02> java DataType.java
Age:25
Salary: 1000.5                            
Grade: A
Is Employed: true
```
---

## String Daya type
* String store text.
```
String name = "Suvendu Mondal";
```
* Example 
```
public class StringDemo {
    public static void main(String[] args) {
        String name = "Suvendu Mondal"; // String data type
        String city = "Kolkata"; // String data type
        System.out.println("Name: " + name);
        System.out.println("City: " + city);
    }
}
```


