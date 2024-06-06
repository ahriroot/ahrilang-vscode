# The A programming language.

`Copyright © 2024-present ahriknow. All rights reserved`

[English](./README.en.md) | [简体中文](./README.zh.md)

## A ？

`A语言，也称为Ahrilang或Alang，被设计成一种简单、快速、用户友好的编程语言。它是一种用于各种任务的通用编程语言。它的设计有利于学习和使用，使其易于阅读和书写。`

## 基本信息

- 网站：[https://lang.ahriknow.com/](https://lang.ahriknow.com/)
- 源码：[https://github.com/ahriroot/ahrilang](https://github.com/ahriroot/ahrilang)
- 问题追踪：[https://github.com/ahriroot/ahrilang/issues](https://github.com/ahriroot/ahrilang/issues)
- 文档：[https://lang.ahriknow.com/docs](https://lang.ahriknow.com/docs)

## 语法

### 变量

```rust
a = 1
b = "hello"
c = true
d = [1, 2, c]
e = {"a": 1, "b": b, c: c, "d": d}
```

### 函数 (异步)

```rust
fn add(a, b){
    return a + b
}

res = add(1, 2)
print(res)

async fn asyncAdd(a, b){
    return a + b
}

task = asyncAdd(1, 2)
res = coroutine(task)
print(res)
```

### If 语句

```rust
a = 0

if a > 0 {
    print("greater than 0")
} else if a < 0 {
    print("less than 0")
} else {
    print("equal to 0")
}
```

### Loop 语句

```rust
a = 0

loop {
    print(a)
    a = a + 1
    if a < 10 {
        continue
    }
    break
}
```

### While 语句

```rust
a = 0

while a < 10 {
    print(a)
    a = a + 1
}
```
