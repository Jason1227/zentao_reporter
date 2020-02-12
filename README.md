# zentao_reporter

一款开源吧禅道报告生成工具，便捷生成一段时间内禅道用户bug、任务相关报告。

## 已实现功能

- [x] BUG创建、激活、关闭、解决、当前待处理BUG情况汇总
- [x] BUG创建详细
- [x] BUG激活详细
- [x] BUG关闭详细
- [x] BUG解决详细
- [x] 当前待处理BUG详细
- [x] 进行的任务，以及当期消耗工时
- [x] 当前待处理任务详细

## TODO
以下是本工具预计增加的功能，也欢迎大家多提意见和参与开发！

- 命令行参数
- 结合crontab实现自动生成日报、周报、月报的文档
- 邮件发送
- 在线查看？
- 在线生成？

## 安装和使用

### 1. 在禅道数据库中运行sql目录中的文件

目的是创建本工具需要查询的视图

### 2. 安装依赖

```bash
pip install -r requirments.txt
```

### 3.结合实际修改配置文件config.py

### 4.修改zentao_reporter.py中的运行入口 "__main__"，修改自己需要的时间段，运行该文件即可

目前运行方式较为简单，后续可以增加命令行参数

### 5.生成报告截图
![img](https://github.com/zcyuefan/zentao_reporter/blob/master/img/report_1.png)

![img](https://github.com/zcyuefan/zentao_reporter/blob/master/img/report_2.png)