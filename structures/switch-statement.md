# Switch statement
*switch statement* used to specify a block of code to be executed, if a specified condition is true.

## Python
**Important!** In Python indentation is really important. 

Morevover, until **version 3.10**, Python never had a feature that implemented what the switch statement does in other programming languages.

```python
match lang:
  case "Python":
    # Do something 

  case "Perl":
    # Do something 

  case "Java":
    # Do something 
    
  case "C++":
    # Do something

  case "Java":
    # Do something 
    
  case _:
    # Do something 
```

## Perl
```perl
switch($var) {
   case 1 { 
    # Do something 
   }
   
   case 2 {
    # Do something
   }
   
   case 3 { 
    # Do something
   }
   
   case 4 { 
    # Do something
   }
   
   case 5 { 
    # Do something
   }
   
   else { 
    # Do something
   }
}
```

## Java
```java
switch (expression) {
  case a:
    // Do something
    break;
    
  case b:
    // Do something
    break;
    
  default:
    // Do something
    break;
}
```

## C++
```cpp
switch (expression) {
  case a:
    // Do something
    break;
    
  case b:
    // Do something
    break;
    
  default:
    // Do something
    break;
}
```
