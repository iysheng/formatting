# Formatting 源码格式自动化调整工具

## 如果喜欢本项目，欢迎star，谢谢

本文件会自动递归遍历**指定文件夹**下的所有文件或者**指定的文件**（默认对`.c`/`.h`/`.cpp`/`.hpp`，也可以改成你想要的文件类型）进行扫描：

- 将源文件编码统一为UTF-8

- 将TAB键替换为4空格


- 将每行末尾多余的空格删除，并统一换行符为'\n'
- 将RT-Thread版权信息的截至年份修改至今年(若文件不涉及此问题，程序会自动忽略)
- 将上海睿赛德版权信息的截至年份修改至今年(若文件不涉及此问题，程序会自动忽略)

## 安装依赖软件包

```shell
pip install -r requirements.txt
```

## 使用方法

### 方法一

直接运行脚本,根据提示信息,输入要扫描的**文件夹或者文件名**即可。

``` shell
▸ python formatting.py
Please enter work path or file to format: test_dir
```

### 方法二

可以直接在命令行参数中指定需要格式化的**文件夹或者文件名**

``` shell
▸ python formatting.py [dir/file_name]
```

或者直接在 linux 下以类似 `./command` 方式直接运行该脚本
``` shell
▸ ./formatting.py [dir/file_name]
```

### 教学视频

> https://www.bilibili.com/video/BV1XN411Q7n3



## 使用协议

本软件为MIT协议，可以自由免费使用，无论是个人目的还是商业目的，但是发现本脚本有任何问题，请提PR协助修复。
