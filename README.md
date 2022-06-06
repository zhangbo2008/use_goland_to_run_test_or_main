# use_goland_to_run_test_or_main



2022-06-06,17点41



goland 运行代码方式:

如果不按照这个来,有可能会遇到找不到库包的情况. 这么设置会保证一定可以运行.



把代码目录文件夹放到
D:\Users\Administrator\go1.16\src\ 
里面
然后运行这个代码里面的main 或者test都会不会发生找不到库包的情况
因为这里面是root目录,会自动扫描.

