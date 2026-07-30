# 按物流跟踪号重命名标签文件

[English](../../../en/shipping-workflows/rename-labels-by-tracking-number.md)

## 问题现象

仓库或运营团队经常拿到一个合并的物流标签 PDF。为了归档、上传到其他系统或后续查找，需要把每一页拆成单独文件，并按跟踪号（tracking number）命名。

## 常见原因

- 平台把很多面单合并导出成一个 PDF。
- `labels.pdf`、`download.pdf` 这类文件名不方便仓库查找某一票货。
- 大批量手动拆分、手动重命名耗时很长。
- 跟踪号在每张面单上，但通常需要通过条码识别更稳定地提取。

## 如何处理

使用 [面单重命名](https://www.autoshipflow.com/zh-cn/tools/label-renamer)：

1. 上传合并的物流标签 PDF。
2. 扫描每一页里的跟踪号。
3. 检查文件名预览。
4. 下载按跟踪号命名的单页标签 ZIP。

## 工具能解决什么，不能解决什么

工具可以拆分合并 PDF，并把每一页按识别到的跟踪号命名。

如果一张标签上有多个条码、跟踪号缺失，或扫描质量较差，命名结果可能需要人工检查。下载和导入其他系统前，建议先确认预览。

## 相关工具

- [面单重命名](https://www.autoshipflow.com/zh-cn/tools/label-renamer)
- [标签 PDF 拆分](https://www.autoshipflow.com/zh-cn/tools/split-label)
- [提取跟踪号](https://www.autoshipflow.com/zh-cn/tools/extract-tracking-numbers)
