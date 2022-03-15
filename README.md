# html2md
一个简单的原生 JS 实现将 HTML 转化为 Markdown 格式的小函数，可用于将剪切板的网页内容变成 markdown 格式

-----

这是两个示例

1. HTML 转换 -- https://kohunglee.github.io/html2md/example/conversion.html
2. 直接粘贴成 markdown 格式 -- https://kohunglee.github.io/html2md/example/Paste_and_convert.html

-----

具体使用可查看示例文件夹

因为制作初期并没有想到会做成完整版，故代码写的比较简单，但对于 99% 的网站，转换绝对够用了。

目前暂不支持 Safari 和 iOS 设备平台，因为这它们不支持`零点断言`这种正则语法，以后有空会优化的。
也暂不支持 WPS 等其他格式的标签语言转换。
