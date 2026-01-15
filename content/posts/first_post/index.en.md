---
title: "The First Article: Basic Test"
subtitle: ""
date: 2026-01-11T10:40:19+08:00
lastmod: 2026-01-11T10:40:19+08:00
draft: false
authors: [Zzz]
description: ""

tags: [Basic Test]
categories: [Test]
series: [Starting Test]

hiddenFromHomePage: false
hiddenFromSearch: false

featuredImage: ""
featuredImagePreview: ""

toc:
  enable: true
math:
  enable: true
lightgallery: true
license: ""
---
This article is mainly used for *testing*, some codes, formulas and other contents.
<!--more-->


## Test code highlighting in various languages

Python example:
```python
def hello_world():
"""This is an example of a Python function."""
name = "Hugo"
print(f"Hello, {name}!")
return f"Welcome to use{name}"

# Call function
result = hello_world()
print(f"结果: {result}")

# List comprehension
numbers = [i for i in range(10) if i % 2 == 0]
print(f"result: {numbers}")
```

JavaScript example:
```javascript
// JavaScript Example code
const greet = (name) => {
console.log(`Hello, ${name}!`);
return `Welcome ${name}`;
};

// Example of asynchronous function
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

// Use
greet('World');
```


> Verify whether the highlighting is working, used to verify whether the code is highlighted!


---
## Verify the formula
\[ c = \pm\sqrt{a^2 + b^2} \]

\[ f(x)=\int_{-\infty}^{\infty} \hat{f}(\xi) e^{2 \pi i \xi x} d \xi \]

---

## Others
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