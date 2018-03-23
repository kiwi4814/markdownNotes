---
typora-root-url: MarkDown\IDEA相关
---

####1.IDEA自动导包

`Settings → Editor → General → Auto Import` 

```
Optimize imports on the fly(自动去掉一些没有用到的包)
Add unambiguous imports on the fly(自动帮我们优化导入的包)
```

#### 2.国际化中文显示：

`Settings —> File Encodings —> 勾选Transpatrent native-to-ascii conversion`

####3.修改编码为UTF-8

`Settings —> File Encodings —> 改为UTF-8`

全局设置在`Other Settings`

```ejs
Error:(1, 1) java: 非法字符: '\ufeff'
```

错误处理方法：NotePad++中打开文件，以UTF-8无BOM格式编码即可

####4.修改tab为四个空格

`Setting(Project Settings)->Code Style->java`

去掉`Use tab character`

