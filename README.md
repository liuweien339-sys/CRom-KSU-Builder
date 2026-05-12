***Read the README first***  
main branch only support android16  
How to use:

Fork this repo(remember to sync before using)  
Turn to Actions page in ur repo  
Select clang version(clang-r547379 for a16qpr0 r563880/r563880c for a16qpr2)  
Select the kernel source code(PixelOS select OnePlus12R-development)  
Enter ur Kernel Branch(See this in ur kernel source repo,such as lineage-23.2 for los 16.0 for crd, sixteen-qpr2 for pos)  
Select the KernelSU/KernelSU forks that u need(susfs maybe broken, it is controlled by simonpunk)  

ksu toolkit:
https://github.com/backslashxx/ksu_toolkit

Inferno's build(ksu ksunext sukisu)
https://github.com/inferno0230/kernel_oneplus_sm8550-CI

***先读说明***
Main分支支持安卓16
怎么用:
Frok这个仓库 
打开Action页面
选择Clang版本 安卓16QPR0用r547379 QPR2用r563880c/r063880
输入内核源码地址
输入你内核源码的分支
选择Root管理器
最后点击Running Workflow进行编译
编译结果包含在Releases里面

我添加了关于RedmiNote9Pro Guaguin LineageOS23.2的支持在Default里面 直接Running Workflow就行 如果你是gauguin  
