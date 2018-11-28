# 上下固定，中间自适应

```
布局要求：上下固定100px,中间自适应。
```


```html
<div>
    <header>我是顶部</header>
    <section>
      <h1>上下固定，中间自适应</h1>
      <p>布局要求：上下固定100px,中间自适应。</p>
    </section>
    <footer>底部</footer>
</div>
```

### 使用calc计算高度
css
```css
 * {
      margin: 0;
      padding: 0;
    }

    header {
      height: 100px;
      background: #eee;
    }

    footer {
      height: 100px;
      background: #eee;
    }

    section {
      background: yellow;
      min-height: calc(100vh - 200px);
    }
```



