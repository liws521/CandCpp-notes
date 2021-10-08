C源文件-预处理-编译-汇编-链接-可执行文件
gcc -v
man gcc
gcc -E hello.c > hello.i
gcc -S hello.i
gcc -c hello.s
gcc hello.o -o hello
./hello

gcc hello.c -o hello

make hello


gcc hello.c -Wall

malloc返回值是void* 不需要强制转换

不包含头文件,没有见到函数原型的函数默认返回类型为整数,常常类型不匹配