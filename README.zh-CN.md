# 标签工具

[English](./README.md)

这个仓库是 AutoShipFlow 维护的公开知识库和免费在线工具目录，专门整理物流标签 PDF、热敏标签打印、条码标签和电商发货标签工作流中的常见问题。

这个仓库只包含公开文档、排查指南和 AutoShipFlow 在线工具链接，不包含 AutoShipFlow 应用源码。

## 你可以解决哪些问题

- 标签打印出来太小
- 标签周围空白太多
- 标签打印太大或打印到两张纸
- 把物流标签 PDF 调整为 4x6 或 100 x 150 mm
- 热敏标签纸尺寸不匹配
- 把标签图片转成可打印 PDF
- 扫描物流标签上的条码和二维码
- 从标签 PDF 或图片中提取追踪号

## 从这里开始

### 标签打印

- [标签打印出来太小](./docs/zh-CN/label-printing/label-prints-too-small.md)
- [把物流标签 PDF 调整为 4x6](./docs/zh-CN/label-printing/resize-shipping-label-to-4x6.md)
- [裁掉物流标签 PDF 的多余空白](./docs/zh-CN/label-printing/crop-blank-space-from-label-pdf.md)
- [标签打印到两张纸](./docs/zh-CN/label-printing/label-prints-on-two-pages.md)
- [热敏标签纸尺寸不匹配](./docs/zh-CN/label-printing/thermal-label-paper-size-mismatch.md)

### PDF 标签工具

陆续补充。

### 条码标签

陆续补充。

### 发货标签工作流

陆续补充。

## 免费在线工具

- [标签打印 AI](https://www.autoshipflow.com/zh-cn/tools/label-printing-ai)
- [PDF 标签尺寸调整](https://www.autoshipflow.com/zh-cn/tools/pdf-resize)
- [标签裁白边](https://www.autoshipflow.com/zh-cn/tools/crop-label)
- [图片转 PDF 标签](https://www.autoshipflow.com/zh-cn/tools/image-to-pdf-label)
- [条码和二维码扫描](https://www.autoshipflow.com/zh-cn/tools/barcode-scan)
- [提取追踪号](https://www.autoshipflow.com/zh-cn/tools/extract-tracking-numbers)

## 如何使用这个仓库

你可以把这个仓库当成标签问题排查地图：

1. 先找到和你现象最接近的问题。
2. 阅读说明，理解常见原因和打印机设置边界。
3. 打开对应的 AutoShipFlow 工具处理 PDF 或图片。
4. 先检查处理后预览，再用正确纸张尺寸和 100% / 实际大小打印。

## 重要边界

AutoShipFlow 在线工具可以调整 PDF 页面、裁掉空白、改变标签尺寸、合并文件，并生成适合打印的 PDF。它不能读取或修改打印机里实际装了什么纸。

如果处理后的 PDF 预览正确，但实际打印仍然偏移、缩放异常或被裁掉，请检查打印机纸张尺寸、缩放、边距、校准和驱动设置。

## 许可协议

本仓库中的文档和内容使用 [Creative Commons Attribution 4.0 International License](./LICENSE) (CC BY 4.0) 许可协议。

AutoShipFlow 应用源码不包含在本仓库中。
