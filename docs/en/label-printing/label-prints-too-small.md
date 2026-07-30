# Shipping Label Prints Too Small

[简体中文](../../../zh-CN/label-printing/label-prints-too-small.md)

## Problem

The shipping label looks normal in the PDF viewer, but it prints very small on thermal label paper. You may see a lot of blank space around the label, or the barcode and address text may become hard to read.

## Common Causes

- The PDF page is larger than the real label paper.
- The label content is surrounded by large blank margins.
- The printer dialog scales the whole PDF page down to fit the selected paper.
- The file includes CropBox or Rotate metadata that changes the visible label size.

## How to Fix It

Use [Label Printing AI](https://www.autoshipflow.com/tools/label-printing-ai):

1. Upload the label PDF or image.
2. Choose the real paper size loaded in your printer, such as 4 x 6 in or 100 x 150 mm.
3. Describe the problem, for example: `the label prints too small with blank space`.
4. Preview the fixed PDF.
5. Print with the same paper size and 100% / Actual size scale.

## What the Tool Can and Cannot Fix

The tool can crop extra blank space, resize the PDF page, merge files, and generate a print-ready PDF.

It cannot detect the paper physically loaded in your printer. If the fixed preview looks correct but the physical print is still shifted or scaled, check printer paper size, scale, margins, calibration, and driver settings.

## Related Tools

- [Label Printing AI](https://www.autoshipflow.com/tools/label-printing-ai)
- [Crop Label](https://www.autoshipflow.com/tools/crop-label)
- [PDF Label Resizer](https://www.autoshipflow.com/tools/pdf-resize)
