# 标签打印出来太小

[English](../../../en/label-printing/label-prints-too-small.md)

## 问题现象

PDF 预览里标签看起来正常，但打印到热敏标签纸上后，标签内容变得很小。常见表现是周围空白很多，条码、地址和文字都被缩小，扫描或阅读变困难。

## 常见原因

- PDF 页面尺寸比真实标签纸大。
- 标签内容周围有大量空白边。
- 打印窗口把整个 PDF 页面缩放到当前纸张里。
- 文件包含 CropBox 或 Rotate 信息，导致可视尺寸和原始页面尺寸不一致。

## 如何处理

使用 [标签打印 AI](https://www.autoshipflow.com/zh-cn/tools/label-printing-ai)：

1. 上传标签 PDF 或图片。
2. 选择打印机里真实装入的纸张尺寸，例如 4 x 6 in 或 100 x 150 mm。
3. 描述问题，例如：`标签打印出来太小，周围空白很多`。
4. 检查处理后预览。
5. 打印时选择相同纸张尺寸，并使用 100% / 实际大小。

## 工具能解决什么，不能解决什么

工具可以裁掉多余空白、调整 PDF 页面尺寸、合并文件，并生成适合打印的 PDF。

它不能检测打印机里实际装了什么纸。如果处理后预览正确，但实际打印仍然偏移或缩放异常，请检查打印机纸张尺寸、缩放、边距、校准和驱动设置。

## 相关工具

- [标签打印 AI](https://www.autoshipflow.com/zh-cn/tools/label-printing-ai)
- [标签裁白边](https://www.autoshipflow.com/zh-cn/tools/crop-label)
- [PDF 标签尺寸调整](https://www.autoshipflow.com/zh-cn/tools/pdf-resize)
