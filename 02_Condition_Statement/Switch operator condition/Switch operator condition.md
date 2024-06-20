
# Switch operator condition


- The expression consists of three operands: the condition, value if true, and value if false.
- The evaluation of the condition should result in either a true/false or a boolean value.
- The true value lies between “?” & “:” and is executed if the condition returns true. Similarly, the false value lies after “:” and is executed if the condition returns false.
Understanding ternary operator.
---
```barh
Switch (expression){
  case condition 1: statement(s)
  break;

  case condition 2: statement(s)
  break;

  case condition 3: statement(s)
  break;

  default: statement(s)
}
```
```barh
var age = 15;

Switch(true){
  case (age >=15 && age <=20):
    document.write("you are eligible");
  break;  
  case (age >=21 && age <=30):
    document.write("you are not eligible");
  break;  

  default:
    document.write("enter valid age")

}
```

----
