# HTML的一些日常指令记录

## 2025.08.12
1. 文本靠右 right右，left左，center中
   
```HTML
<div align="right">...</div> 
# 建议更改
<div style="text-align: right;">...</div>
```

2. 打开的链接，并新标签页打开
   
```HTML
<a href="URL" target="_blank">显示的内特容</a>
```

3. 文字位置和显示的内容

```HTML
<div align='left'><a href="URL">示例链接</a></div>
# 建议修改
<div style="text-align: right;">
    <a href="URL" target="_blank">实例链接</a>
</div>
```

4. 强制换行

```HTML
<br>
```

5. 加粗，字体，文本位置，字号大小
<h1 style="text-align: center;font-family: 'Microsoft YaHei'; font-size: 48px;">示例文本</h1>

6. 自动换行
```HTML
<div style="page-break-after: always;"></div>
```