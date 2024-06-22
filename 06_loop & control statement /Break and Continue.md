
# Break and Continue
- The break statement "jumps out" of a loop.

- The continue statement "jumps over" one iteration in the loop.

break
---
```bash
for (var a =1; a<= 10; a++){
  if  (a == 3){
    document.write("hey : " + a + "<br>");
    break;
  }
  document.write("number : " + a + "<br>");
}
```

continue
---
```bash
for (var a =1; a<= 10; a++){
  if  (a == 3){
    document.write("hey : " + a + "<br>");
    continue;
  }
  document.write("number : " + a + "<br>");
}
```
----
