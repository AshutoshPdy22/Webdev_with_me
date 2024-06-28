
# nested loop

Advance problem 1
---
|  A  |  B   |
|:------     |:-------|
|      1      |   1     |
|       2     |      12  |
|         3 |     123   |
|         4   |    1234    |
|         5   |    12345    |
- solution
```bash
for (var a=1;a<=5;a++){
  for (var b=1;b <=a;b++){
    document.write(b);
  }
}
```
Advance problem 2
---
|A|  B |
|:------     |:-------|
|      1      |   1     |
|       2     |      22  |
|         3 |     333   |
|         4   |    4444    |
|         5   |    55555    |

```bash
for (var a =1;a<=5;a++){
  for (var b=1;b<=a;b++){
    document.write(a);
  }
}
```
Advance problem 3
--

|A|  B |
|:------     |:-------|
|      5     |   55555     |
|       4     |      4444  |
|         3 |     333   |
|         2   |    22    |
|         1   |    1    |

```bash
for (var a =5;a<=1;a--){
  for (var b=1;b<=a;b++){
    document.write(a);
  }
  document.write("<br>");
}
```
Advance problem 4
--

|A|  B |
|:------     |:-------|
|      5     |   54321     |
|       4     |      4321 |
|         3 |     321   |
|         2   |    21   |
|         1   |    1    |

```bash
for (var a =5;a>=1;a--){
  for (var b=a;b<=1;b--){
    document.write(b);
  }
  document.write("<br>");
}
```

----
