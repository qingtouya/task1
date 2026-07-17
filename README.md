\# CSV数据处理小项目

\## 项目功能

读取学生各科成绩CSV表格，完成科目分数统计、及格人员筛选、分数频次统计，导出结构化JSON结果文件。

\## 运行环境

Python版本：3.9及以上

第三方依赖：pandas

\## 安装依赖命令

打开终端，进入项目根目录执行：

pip install pandas

\## 启动运行命令

终端定位到项目根目录，输入：

python src/main.py

\## 目录与输出说明

1\. data/student.csv：原始输入数据源文件

2\. src/main.py：主程序处理脚本

3\. result.json：程序运行后自动生成，存放所有处理结果，位于项目根目录

\## 问题与解决

问题：导出JSON中文出现乱码。

解决：文件写入指定utf-8编码，json.dump添加ensure\_ascii=False参数。

本次迭代完善数据处理逻辑

处理

