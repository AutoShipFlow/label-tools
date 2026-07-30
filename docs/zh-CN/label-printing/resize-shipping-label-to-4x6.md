# 把物流标签 PDF 调整为 4x6

[English](../../../en/label-printing/resize-shipping-label-to-4x6.md)

## 问题现象

很多平台或承运商导出的标签 PDF 是 A4、Letter，或者尺寸略大于 4 x 6 in。直接用热敏打印机打印时，可能出现标签太小、太大、空白多或纸张不匹配。

## 常见原因

- 导出的 PDF 页面并不是标准 4 x 6 in。
- 标签内容嵌在更大的页面里。
- 文件包含 CropBox 或 Rotate 信息，影响可视方向和尺寸。
- 打印窗口选择的纸张尺寸和 PDF 不一致。

## 如何处理

使用 [标签打印 AI](https://www.autoshipflow.com/zh-cn/tools/label-printing-ai)：

1. 上传物流标签 PDF。
2. 目标纸张选择 `4 x 6 in`。
3. 描述问题，例如：`把这个物流标签调整为 4x6`。
4. 检查处理后预览。
5. 打印时选择 4 x 6 in 纸张，并使用 100% / 实际大小。

## 工具能解决什么，不能解决什么

工具可以把可视标签内容适配到 4 x 6 in，安全裁掉空白，并尽量保持条码和文字完整。

它不能修改打印机驱动设置。如果 PDF 预览正确但打印不对，请检查浏览器打印窗口和打印机驱动里的纸张尺寸。

## 相关工具

- [标签打印 AI](https://www.autoshipflow.com/zh-cn/tools/label-printing-ai)
- [PDF 标签尺寸调整](https://www.autoshipflow.com/zh-cn/tools/pdf-resize)
- [图片转 PDF 标签](https://www.autoshipflow.com/zh-cn/tools/image-to-pdf-label)
