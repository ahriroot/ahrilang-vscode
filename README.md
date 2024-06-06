# The A programming language.

`Copyright © 2024-present ahriknow. All rights reserved`

[English](./README.en.md) | [简体中文](./README.zh.md)

## What is A?

`The A programming language, also known as Ahrilang or Alang, is designed to be a simple, fast, and user-friendly programming language. It is a general-purpose programming language intended for a variety of tasks. Its design is conducive to learning and usage, making it easy to read and write.`

## General Information

- Website: [https://lang.ahriknow.com/](https://lang.ahriknow.com/)
- Source code: [https://github.com/ahriroot/ahrilang](https://github.com/ahriroot/ahrilang)
- Issue tracker: [https://github.com/ahriroot/ahrilang/issues](https://github.com/ahriroot/ahrilang/issues)
- Documents: [https://lang.ahriknow.com/docs](https://lang.ahriknow.com/docs)

## Grammar

### Variables

```rust
a = 1
b = "hello"
c = true
d = [1, 2, c]
e = {"a": 1, "b": b, c: c, "d": d}
```

### Function (Async)

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

### If Statement

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

### Loop Statement

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

### While Statement

```rust
a = 0

while a < 10 {
    print(a)
    a = a + 1
}
```
