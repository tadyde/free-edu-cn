# Python入门学习指南

> 零基础友好，适合所有专业学生

## 为什么要学Python

- 语法简洁，入门容易
- 应用广泛：数据分析、人工智能、Web开发、自动化
- 就业市场需求大
- 社区活跃，学习资源丰富

## 环境搭建

1. 下载Python：https://www.python.org/downloads/
2. 安装时勾选"Add Python to PATH"
3. 验证：打开命令行输入 python --version

## 基础语法

### 变量与数据类型
`python
name = "张三"      # 字符串
age = 20           # 整数
score = 95.5       # 浮点数
is_student = True  # 布尔值
`

### 条件判断
`python
if score >= 90:
    print("优秀")
elif score >= 60:
    print("及格")
else:
    print("不及格")
`

### 循环
`python
for i in range(10):
    print(i)

while count > 0:
    count -= 1
`

### 列表
`python
fruits = ["苹果", "香蕉", "橘子"]
fruits.append("葡萄")
for fruit in fruits:
    print(fruit)
`

### 函数
`python
def greet(name):
    return f"你好，{name}！"

result = greet("李四")
print(result)
`

### 字典
`python
student = {
    "name": "王五",
    "age": 21,
    "major": "计算机"
}
print(student["name"])
`

## 推荐学习路线

1. 基础语法（1-2周）
2. 数据结构：列表、字典、元组、集合（1周）
3. 函数与模块（1周）
4. 文件操作与异常处理（1周）
5. 面向对象编程（2周）
6. 常用库：requests, pandas, matplotlib（按需学习）

## 推荐资源

- 官方教程：https://docs.python.org/zh-cn/3/tutorial/
- 菜鸟教程：https://www.runoob.com/python3/python3-tutorial.html
- B站搜索"Python入门"有大量免费视频教程

## 学习建议

1. 每天写代码，哪怕只有30分钟
2. 不要只看视频不动手，边看边敲
3. 遇到报错不要怕，学会阅读错误信息
4. 做小项目练手：计算器、猜数字、记事本
5. 学会搜索：遇到问题先搜索，90%的问题别人遇到过