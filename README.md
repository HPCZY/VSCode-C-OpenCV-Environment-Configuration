# VSCode-C-OpenCV-Environment-Configuration

**Bilibili UP: [今天不飞了](https://space.bilibili.com/330337755)**
  [**如果对你有帮助，可以帮我点亮右上角的五角星，感谢**]
  
记录+分享我配置VS Code/C++/OpenCV的成功案例。
注：该环境配置于2023年3月，很多年后的网友就不要参考了。


## 下载文件

**VS Code**<br>
下载地址：[https://code.visualstudio.com/](https://code.visualstudio.com/)<br>
我的版本：VSCode-x64-1.76.0(官网最新版)<br>

**MinGW**<br>
下载地址：[https://sourceforge.net/projects/mingw-w64/files/mingw-w64/](https://sourceforge.net/projects/mingw-w64/files/mingw-w64/)<br>
我的版本：MinGW-W64 GCC-8.1.0-x86_64-posix-sjlj (官网最新版)<br>
原因：尝试了几次`win32`版都失败了（因为我看的第一个资料说用`win32`），查更多资料后选择`posix`，且`sjlj`（前辈说报错率比seh低）<br>

**cmake**<br>
下载地址：[https://cmake.org/files/v3.24/](https://cmake.org/files/v3.24/)<br>
我的版本：cmake-3.24.4-windows-x86_64.zip (官网最新版)<br>

**OpenCV**<br>
下载地址：[https://opencv.org/releases/](https://opencv.org/releases/)<br>
我的版本：OpenCV–4.6.0-windows<br>
原因：网友都说最新版可能不稳定，就选的次新版<br>

注：上文中提到的“最新版”均为2023年3月存在的最新版本。<br>


## 安装文件

**VS Code**<br>
文件类型：EXE可执行文件(直接安装)<br>
推荐路径：D盘<br>
我的路径：`D:\VSCode` <br>

**MinGW**<br>
文件类型：7Z压缩文件(直接解压)<br>
推荐路径：D盘<br>
我的路径：`D:\ENV\MinGW` <br>

**cmake**<br>
文件类型：ZIP压缩文件(直接解压)<br>
推荐路径：C盘（因为网友说放其他盘可能编译报错，我直接信了没有验证）<br>
我的路径：`C:\ENV\Cmake` <br>

**OpenCV**<br>
文件类型：EXE可执行文件(直接安装)<br>
推荐路径：D盘<br>
我的路径：`D:\ENV\OpenCV` <br>


注：用上述路径配了两台别人的电脑都成功，我的电脑C盘为256G固态硬盘，所以综合考虑直接全放C盘了，如下：<br>
`C:\ENV\VSCode` <br>
`C:\ENV\MinGW` <br>
`C:\ENV\Cmake` <br>
`C:\ENV\OpenCV` <br>


## Cmake你的OpenCV源码





## 配置VS code环境






## 测试代码










## 补充说明

网上资料繁杂，每个人配置过程或多或少都会遇到



