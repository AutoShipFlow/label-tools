# Resize Shipping Label PDF to 4x6

[简体中文](../../../zh-CN/label-printing/resize-shipping-label-to-4x6.md)

## Problem

Many shipping platforms and carrier portals export labels as A4, Letter, or slightly oversized PDF pages. If you print those files directly on a 4 x 6 in thermal printer, the label may print too small, too large, or with extra blank space.

## Common Causes

- The exported PDF page is not exactly 4 x 6 in.
- The label is embedded inside a larger page.
- The file has CropBox or Rotate metadata that affects the visible orientation.
- The printer dialog uses a different paper size from the PDF.

## How to Fix It

Use [Label Printing AI](https://www.autoshipflow.com/tools/label-printing-ai):

1. Upload the shipping label PDF.
2. Choose `4 x 6 in` as the target paper size.
3. Describe the issue, such as `resize this shipping label to 4x6`.
4. Review the fixed preview.
5. Print with 4 x 6 in paper and 100% / Actual size scale.

## What the Tool Can and Cannot Fix

The tool can fit the visible label to 4 x 6 in, crop safe blank space, and preserve barcode and text as much as possible.

It cannot change printer driver settings. If the PDF preview is correct but printing is not, check the paper size selected in your browser and printer driver.

## Related Tools

- [Label Printing AI](https://www.autoshipflow.com/tools/label-printing-ai)
- [PDF Label Resizer](https://www.autoshipflow.com/tools/pdf-resize)
- [Image to PDF Label](https://www.autoshipflow.com/tools/image-to-pdf-label)
