## Encapsulation

### Another way to think about encapsulation is that it is a protective shield that prevents the data from being accessed by the code outside this shield. 

1)Encapsulation is the process of combining data and functions into a single unit called class



2)In Encapsulation, the data is not accessed directly; it is accessed through the functions present inside the class



3)In simpler words, attributes of the class are kept private and public getter and setter methods are provided to manipulate these attributes.



4)Thus, encapsulation makes the concept of data hiding possible.


## Data hiding: 

A language feature to restrict access to members of an object, reducing the negative effect due to dependencies. e.g. "protected", "private" feature in Java


```
//Encapsulation using private modifier 
  
//Employee class contains private data called employee id and employee name
class Employee {
    private int empid;
      private String ename;
}
```
