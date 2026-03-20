# 多标签示例

本页面展示 docsify 多标签功能的各种用法。

---

## 基础用法

<!-- tabs:start -->

#### **标签 1**

这是标签 1 的内容。

#### **标签 2**

这是标签 2 的内容。

#### **标签 3**

这是标签 3 的内容。

<!-- tabs:end -->

---

## 代码示例标签

<!-- tabs:start -->

#### **JavaScript**

```javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
}

greet('World');
```

#### **Python**

```python
def greet(name):
    print(f"Hello, {name}!")

greet("World")
```

#### **Java**

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

<!-- tabs:end -->

---

## 安装指南标签

<!-- tabs:start -->

#### **npm**

```bash
npm install docsify-cli -g
docsify init ./docs
docsify serve docs
```

#### **CDN**

直接在 HTML 中引入：

```html
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify@4/lib/themes/vue.css">
<script src="//cdn.jsdelivr.net/npm/docsify@4"></script>
```

#### **GitHub Pages**

1. 创建仓库
2. 上传 docs 文件
3. 开启 GitHub Pages

<!-- tabs:end -->

---

## 嵌套标签

<!-- tabs:start -->

#### **前端**

<!-- tabs:start -->

#### **React**

```jsx
function App() {
  return <h1>Hello React!</h1>;
}
```

#### **Vue**

```vue
<template>
  <h1>Hello Vue!</h1>
</template>
```

#### **Angular**

```typescript
@Component({
  template: '<h1>Hello Angular!</h1>'
})
export class AppComponent {}
```

<!-- tabs:end -->

#### **后端**

<!-- tabs:start -->

#### **Node.js**

```javascript
const express = require('express');
const app = express();

app.get('/', (req, res) => {
  res.send('Hello Node.js!');
});
```

#### **Python (Flask)**

```python
from flask import Flask
app = Flask(__name__)

@app.route('/')
def hello():
    return 'Hello Flask!'
```

<!-- tabs:end -->

<!-- tabs:end -->

---

## 自定义样式标签

<!-- tabs:start -->

#### **成功**

> ✓ 操作成功！数据已保存。

#### **警告**

> ⚠️ 请注意，此操作不可逆。

#### **错误**

> ✗ 发生错误，请稍后重试。

#### **信息**

> ℹ 这是一条提示信息。

<!-- tabs:end -->