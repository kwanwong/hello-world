###随笔###

*Git Bash中使用Sublime打开文件*

> 新建一个文件命名为你想要的命令，比如sublime(不能有后缀名)，内容:

    #!/bin/sh
    "C:\Program Files\Sublime Text 3\subl.exe" $1 &
    //第一行是说这是个shell脚本
    //第二行为Sublime的安装目录
    //第二行的$1是取命令后输入的参数
    //第二行的&是指该命令在后台打开，这样Sublime打开之后不会阻塞Git Bash

> 将文件保存到C:\Program Files\Git\mingw64\bin目录(Git安装目录)

###
