linux--gcc--
============
####有关代码编辑：####

    用cd命令选择一个文件夹，用sudu vim hello.c     
    建立一个新的c文件；进入代码编辑(其中按i可进入编辑状态，按Esc退出编辑状态，输入wq可以保存退出）
    
####有关编译：####

    输入以下命令进行编译：
    gcc -E hello.c -o hello.i
    gcc -S hello.i -o hello.s
    gcc -c hello.i -o hello.o
    gcc hello.o -o hello
    ./hello                        (这一步运行程序)
    有木有觉得这几不好麻烦啊。。。所以又就下来的方法进行简化
    
####[Linux下GCC和Makefile实例（从GCC的编译到Makefile的引入）](http://www.crazyant.net/414.html)####

    
