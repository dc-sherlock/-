# 编译原理  
## makefile
```
flex lex.l   
bison -d parser.y  
gcc -o obj lex.yy.c parser.tab.c ast.c semantic_Analysis.c symbol.c code.c objectCode.c  
```  
对编译原理的学习过程以及课程实验、课程设计的记录，上述为代码的编译方法。  
使用flex工具操作lex.l文件生成词法分析程序  
使用bison工具操作parser.y文件生成语法分析程序  
