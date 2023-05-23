1、compile the .y file with command
```bash
 yacc -dv mycalc.y 
 ```
2、compile the .l file with command
```bash
 lex mycalc.l
 ```
3、compile the .c file with command
```bash
 gcc -o mycalc y.tab.c lex.yy.c
 ```
4、now you can run the program with command
```bash
 ./mycalc
 ```
5、the running result of the calculator is as follows:
![result](/my-calc/images/result.png)
 
 
