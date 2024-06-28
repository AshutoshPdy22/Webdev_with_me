
# nested loop
A composition of loops is called a nested loop. The most common type of nested loops will be one loop inside another. The first loop is usually called the outer loop while the second loop is called the inner loop.

nested loop
---
```bash
for (var a =1; a<= 100; a=a+10){
  for (var b =a; b < a+10 ; b++){
    document.write(b+ " ");
  }
  document.write("<br>");
}  
```
----
