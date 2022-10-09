# 配置
![image](https://user-images.githubusercontent.com/48793634/194750350-c720d2c0-36e8-48d6-8a81-9d5697bd6bab.png)

Output directory: 输出的dll/exe文件存放处

设置 Working directory: 当前工作目录，exe调用目录/dll没有太大意义
所有相对路径以exe的working directory 为准，调用dll 的代码后也是

#include 有两种情况
①是以当前cpp所在目录为相对路径，索引头文件
②配置的路径中找
③头文件写C/C++ Additional include directories，linker里additional library directories


# 改变工作目录
cmd 
  cd /d (path)D:\MCSF_CY\MCSF\BRANCH\ZHENGHE_69_SP4\UIH\bin & (exe)McsfAlgoVessel_UT.exe

python
  os.chdir()
