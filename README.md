# Formatting 源码格式自动化调整工具

本文件会自动对指定路径下的所有文件包括子文件夹的文件（默认对.c/.h/.cpp，也可以改成你想要的文件类型）进行扫描：

- 将源文件编码统一为UTF-8
- 将TAB键替换为空格
- 将每行末尾多余的空格删除，并统一换行符为'\n'
- 将RT-Thread版权信息的截至年份修改至今年 (代码中不含此问题的可无视本功能，程序会自动略过)
- 将上海睿赛德版权信息的截至年份修改至今年 (代码中不含此问题的可无视本功能，程序会自动略过)


使用时只需要双击本文件，输入要扫描的文件夹路径即可。



教学视频：https://www.bilibili.com/video/BV1XN411Q7n3



不要忘记先安装依赖软件包：

```shell
pip install -r requirements.txt
```

