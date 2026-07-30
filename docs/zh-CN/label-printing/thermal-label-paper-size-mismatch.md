# 热敏标签纸尺寸不匹配

[English](../../../en/label-printing/thermal-label-paper-size-mismatch.md)

## 问题现象

PDF 标签尺寸和热敏打印机里实际装入的纸张不匹配。标签可能打印太小、太大、偏移、被裁掉，或者打印到多张纸。

## 常见原因

- PDF 文件页面尺寸和真实标签纸不一致。
- 打印机驱动里选择了另一种纸张预设。
- 浏览器打印窗口应用了缩放或边距。
- 标签纸是 4 x 6 in，但文件更接近 100 x 150 mm，或反过来。

## 如何处理

使用 [标签打印 AI](https://www.autoshipflow.com/zh-cn/tools/label-printing-ai) 先处理文件：

1. 选择打印机里真实装入的纸张尺寸。
2. 上传 PDF 或图片。
3. 描述不匹配现象，例如：`纸张尺寸和我的 100x150 标签纸不匹配`。
4. 检查生成的 PDF 预览。
5. 打印窗口里选择相同纸张尺寸，并使用 100% / 实际大小。

## 工具能解决什么，不能解决什么

工具可以调整 PDF 页面尺寸和版式，也可以在源文件比例和目标纸张差异很大时提醒你检查。

它不能读取打印机里实际装了什么纸，也不能修改打印机驱动预设。如果预览正确但实际打印偏移，剩下的问题大概率是打印机配置。

## 相关工具

- [标签打印 AI](https://www.autoshipflow.com/zh-cn/tools/label-printing-ai)
- [PDF 标签尺寸调整](https://www.autoshipflow.com/zh-cn/tools/pdf-resize)
- [图片转 PDF 标签](https://www.autoshipflow.com/zh-cn/tools/image-to-pdf-label)
