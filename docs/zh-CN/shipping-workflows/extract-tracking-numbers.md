# 从标签 PDF 或图片中提取物流跟踪号

[English](../../../en/shipping-workflows/extract-tracking-numbers.md)

## 问题现象

你有一批物流标签，需要把跟踪号（tracking number）复制到 ERP、WMS、表格、客服系统或承运商查轨迹页面。逐个打开面单手动识别和复制，速度慢，也容易漏位或复制错。

## 常见原因

- 物流标签以 PDF 或图片形式导出，不是结构化数据。
- 跟踪号通常编码在条码里，但可见文字可能很小或不清晰。
- 同一批文件可能混合 USPS、UPS、FedEx、DHL、Amazon 等标签。
- 手动复制很容易出现少一位、多一位或对应错标签的问题。

## 如何处理

使用 [提取跟踪号](https://www.autoshipflow.com/zh-cn/tools/extract-tracking-numbers)：

1. 上传 PDF 或图片标签。
2. 在浏览器中扫描标签。
3. 检查推荐识别出的跟踪号。
4. 复制结果，或下载 CSV 用于后续流程。

## 工具能解决什么，不能解决什么

工具可以扫描标签条码，并从标签文件中识别可能的跟踪号。

但不能保证标签上的每一个条码都是主跟踪号。有些面单还包含订单条码、仓库条码、退货码或承运商路由码。批量使用前，建议先快速检查结果。

## 相关工具

- [提取跟踪号](https://www.autoshipflow.com/zh-cn/tools/extract-tracking-numbers)
- [条码和二维码扫描](https://www.autoshipflow.com/zh-cn/tools/barcode-scan)
- [面单重命名](https://www.autoshipflow.com/zh-cn/tools/label-renamer)
