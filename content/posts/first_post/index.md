---
title: "第一篇文章「基础测试」"
subtitle: ""
date: 2026-01-11T10:40:19+08:00
lastmod: 2026-01-11T10:40:19+08:00
draft: false
authors: [Zzz]
description: ""

tags: [基础测试]
categories: [测试]
series: [起步测试]

hiddenFromHomePage: false
hiddenFromSearch: false

featuredImage: ""
featuredImagePreview: ""

toc:
  enable: true
math:
  enable: true
lightgallery: false
license: ""
---
这篇文章主要用来*测试*，一些代码、公式等内容。
<!--more-->


## 测试各种语言的代码高亮

Python 示例：  
```python
def hello_world():
    """这是一个Python函数示例"""
    name = "Hugo"
    print(f"Hello, {name}!")
    return f"欢迎使用{name}"

# 调用函数
result = hello_world()
print(f"结果: {result}")

# 列表推导式
numbers = [i for i in range(10) if i % 2 == 0]
print(f"偶数: {numbers}")
```

JavaScript 示例：  
```javascript
// JavaScript 代码示例
const greet = (name) => {
    console.log(`Hello, ${name}!`);
    return `Welcome ${name}`;
};

// 异步函数示例
async function fetchData(url) {
    try {
        const response = await fetch(url);
        const data = await response.json();
        return data;
    } catch (error) {
        console.error('Error:', error);
        throw error;
    }
}

// 使用
greet('World');
```


> 验证高亮是否工作，用来验证代码是否高亮显示！  

---
## 验证公式  
\[ c = \pm\sqrt{a^2 + b^2} \]

\[ f(x)=\int_{-\infty}^{\infty} \hat{f}(\xi) e^{2 \pi i \xi x} d \xi \]

---

## 其他
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.