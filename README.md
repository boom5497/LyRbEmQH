## 前言

基于SSM的高校成绩报送系统，旨在帮助高校教师和学生解决成绩管理的问题，提高教育教学质量。本项目采用Java语言，结合Spring、Spring MVC和MyBatis框架，以及前端技术Vue、JS和CSS3，致力于打造一个易用、高效、稳定的高校成绩报送系统。

## 内容介绍

本项目主要包括以下几个模块：

1. 教师模块：教师可以录入、修改、查询学生成绩，以及提交成绩。
2. 学生模块：学生可以查询自己的成绩，了解学习情况。
3. 管理员模块：管理员负责维护教师和学生的基本信息，以及系统设置等。

系统功能齐全，操作简便，适用于各类高校。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Spring MVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下为项目中的一段核心代码，展示成绩查询功能：

```java
// 成绩查询接口
@RequestMapping(value = "/queryScore", method = RequestMethod.GET)
public List<StudentScoreVO> queryScore(@RequestParam("studentId") Integer studentId) {
    List<StudentScoreVO> scoreList = studentService.queryScore(studentId);
    return scoreList;
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/333831/33/11987/154344/68c280eaFab47bb08/febfc771bd3e25b3.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/336079/32/9630/34221/68c280c1F70cf3aae/31ed87b21afd1631.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/339137/17/9420/100733/68c280c1Ff8156799/2f8c8d0ec40bf858.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/329095/38/11982/1720/68c280c2Fde921068/7448aa4bac9e7ff9.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/349048/33/2145/27535/68c280c2Fcbaa1476/711f607f6c4801a0.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/339483/5/9280/35237/68c280c2Fa86ed00b/2e3149ec67f93fee.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/347580/26/2212/42876/68c280c3Fe7ee6be3/8e4425b3380957ec.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/331387/30/11983/49433/68c280c3F30502620/d5a63e498e920cd4.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/339737/36/9143/50169/68c280c4F55319812/d9d46a6ec39ba227.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/346958/38/2200/72344/68c280c4F9157cd59/411781ca9c8fb78f.jpg)
