注册后即可在设备列表中出现Nama Virtual Camera。</br>
运行NamaExample然后勾选摄像头选择框旁边的虚拟化，程序会自动传输数据到虚拟摄像头。


## 注册虚拟摄像头
cd Release  </br>
regsvr32 ./VirtualCamera.dll
## 卸载虚拟摄像头
cd Release  </br>
regsvr32 /u ./VirtualCamera.dll
## 调试工具
graphedt.exe 插入一个Video Capture Source-->Nama Virtual Camera和一个DirectShow Filters-->Video Render。然后将二者触角连接起来。点击界面上端的绿色run按钮，就可以预览摄像头内容了。
祝好运。
