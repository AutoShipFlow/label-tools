# 标签工具

[English](./README.md)

这个仓库是 AutoShipFlow 维护的公开知识库和免费在线工具目录，专门整理物流标签 PDF、热敏标签打印、条码标签和电商发货标签工作流中的常见问题。

这个仓库只包含公开文档、排查指南和 AutoShipFlow 在线工具链接，不包含 AutoShipFlow 应用源码。

## 选择你遇到的标签问题

先从你看到的问题出发，再选择阅读排查文档，或直接打开对应的在线工具处理文件。

### 打印尺寸和纸张不匹配

适合处理标签打印太小、太大、空白太多、打印到两张纸，或和热敏标签纸尺寸不匹配的问题。

- **标签打印出来太小**：裁掉多余空白，并把标签适配到真实纸张尺寸。 [📖 详情](./docs/zh-CN/label-printing/label-prints-too-small.md) · [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/label-printing-ai)
- **把物流标签 PDF 调整为 4x6**：把平台或承运商导出的标签调整为常见 4 x 6 in 热敏标签纸。 [📖 详情](./docs/zh-CN/label-printing/resize-shipping-label-to-4x6.md) · [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/label-printing-ai)
- **裁掉标签 PDF 的多余空白**：去掉大白边，避免标签内容被缩得很小。 [📖 详情](./docs/zh-CN/label-printing/crop-blank-space-from-label-pdf.md) · [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/crop-label)
- **标签打印到两张纸**：把一个完整标签适配到一张目标标签纸上。 [📖 详情](./docs/zh-CN/label-printing/label-prints-on-two-pages.md) · [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/label-printing-ai)
- **热敏标签纸尺寸不匹配**：区分 PDF 文件尺寸问题和打印机纸张、缩放、边距或驱动设置问题。 [📖 详情](./docs/zh-CN/label-printing/thermal-label-paper-size-mismatch.md) · [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/label-printing-ai)

### PDF 标签文件准备

适合在打印、发送给仓库或批量处理前，先整理标签 PDF 或标签图片。

- **调整 PDF 标签页面尺寸**：把标签 PDF 改成 4x6、4x4、100 x 150 mm 或自定义标签纸尺寸。 [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/pdf-resize)
- **裁剪 PDF 标签内容**：裁掉空白区域，或手动裁出指定标签区域。 [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/crop-label)
- **把标签图片转成 PDF**：把 PNG、JPG、WebP 标签图片转成可打印 PDF。 [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/image-to-pdf-label)

### 条码和二维码标签

适合从物流标签、产品标签和仓库标签中读取条码数据。

- **扫描物流标签上的条码和二维码**：从 PDF 或图片中读取 Code 128、QR、Data Matrix、PDF417 等标签条码。 [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/barcode-scan)

### 追踪号工作流

适合按追踪号整理一批物流标签文件。

- **从标签 PDF 或图片中提取追踪号**：不用逐个文件手动看面单，直接复制或整理追踪号。 [📖 详情](./docs/zh-CN/shipping-workflows/extract-tracking-numbers.md) · [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/extract-tracking-numbers)
- **按追踪号重命名物流标签文件**：拆分合并 PDF，并按追踪号下载单页标签文件，方便仓库归档或 ERP 导入。 [📖 详情](./docs/zh-CN/shipping-workflows/rename-labels-by-tracking-number.md) · [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/label-renamer)
- **拆分合并的物流标签 PDF**：把一个多页面单 PDF 拆成单个标签文件。 [📖 详情](./docs/zh-CN/shipping-workflows/split-merged-shipping-label-pdf.md) · [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/split-label)

### 标签编辑和仓库标签

适合添加内部备注、遮盖旧内容，或制作小型仓库标签。

- **编辑物流标签内容**：给 PDF 或图片标签添加 SKU、库位、拣货备注，或用白底遮盖旧内容。 [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/label-editor)
- **生成 SKU、产品和库位标签**：制作带文字、条码或二维码的可打印 SKU 标签，用于仓库和库存流程。 [🚀 体验](https://www.autoshipflow.com/zh-cn/tools/sku-label-generator)

## 免费在线工具

- [标签打印 AI](https://www.autoshipflow.com/zh-cn/tools/label-printing-ai)
- [PDF 标签尺寸调整](https://www.autoshipflow.com/zh-cn/tools/pdf-resize)
- [标签裁白边](https://www.autoshipflow.com/zh-cn/tools/crop-label)
- [图片转 PDF 标签](https://www.autoshipflow.com/zh-cn/tools/image-to-pdf-label)
- [条码和二维码扫描](https://www.autoshipflow.com/zh-cn/tools/barcode-scan)
- [提取追踪号](https://www.autoshipflow.com/zh-cn/tools/extract-tracking-numbers)
- [面单重命名](https://www.autoshipflow.com/zh-cn/tools/label-renamer)
- [标签 PDF 拆分](https://www.autoshipflow.com/zh-cn/tools/split-label)
- [标签编辑器](https://www.autoshipflow.com/zh-cn/tools/label-editor)
- [SKU 标签生成器](https://www.autoshipflow.com/zh-cn/tools/sku-label-generator)

## 如何使用这个仓库

你可以把这个仓库当成标签问题排查地图：

1. 先找到和你现象最接近的问题。
2. 阅读说明，理解常见原因和打印机设置边界。
3. 打开对应的 AutoShipFlow 工具处理 PDF 或图片。
4. 先检查处理后预览，再用正确纸张尺寸和 100% / 实际大小打印。

## 内容策略

查看 [Content Strategy](./CONTRIBUTING-CONTENT.md)，了解这个仓库如何区分稳定排查文档和开放式 GitHub issue 场景收集。

## 重要边界

AutoShipFlow 在线工具可以调整 PDF 页面、裁掉空白、改变标签尺寸、合并文件，并生成适合打印的 PDF。它不能读取或修改打印机里实际装了什么纸。

如果处理后的 PDF 预览正确，但实际打印仍然偏移、缩放异常或被裁掉，请检查打印机纸张尺寸、缩放、边距、校准和驱动设置。

## 许可协议

本仓库中的文档和内容使用 [Creative Commons Attribution 4.0 International License](./LICENSE) (CC BY 4.0) 许可协议。

AutoShipFlow 应用源码不包含在本仓库中。
