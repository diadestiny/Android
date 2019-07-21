# 数据保存技术

## 1.使用命令进入SqLite命令模式

### adb shell sqlite3 /data/data/package_name/databases/  something.db 

## 2.查看表结构以及其它命令

### .tables //显示所有表
### .schema //显示数据库的schema
### select * from Book; //查询语句 踩坑点:1.表名Book还是book 2.加分号

## 3.学习郭神litepal框架的使用
### [litepal链接](https://github.com/LitePalFramework/LitePal)