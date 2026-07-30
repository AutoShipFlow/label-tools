# Thermal Label Paper Size Mismatch

[简体中文](../../../zh-CN/label-printing/thermal-label-paper-size-mismatch.md)

## Problem

The PDF label size and the paper loaded in the thermal printer do not match. The label may print too small, too large, shifted, cut off, or on more than one page.

## Common Causes

- The PDF file uses a different page size from the real label paper.
- The printer driver has a different paper preset selected.
- The browser print dialog applies scaling or margins.
- The label roll is 4 x 6 in, but the file is closer to 100 x 150 mm, or the other way around.

## How to Fix It

Use [Label Printing AI](https://www.autoshipflow.com/tools/label-printing-ai) to prepare the file:

1. Choose the real paper size loaded in the printer.
2. Upload the PDF or image.
3. Describe the mismatch, such as `the paper size does not match my 100x150 label paper`.
4. Preview the generated PDF.
5. In the print dialog, choose the same paper size and 100% / Actual size scale.

## What the Tool Can and Cannot Fix

The tool can adjust the PDF page size and layout. It can also warn when the source file ratio is very different from the target paper.

It cannot read the physical paper loaded in the printer or change printer driver presets. If the preview is correct but physical printing is shifted, the remaining problem is likely printer configuration.

## Related Tools

- [Label Printing AI](https://www.autoshipflow.com/tools/label-printing-ai)
- [PDF Label Resizer](https://www.autoshipflow.com/tools/pdf-resize)
- [Image to PDF Label](https://www.autoshipflow.com/tools/image-to-pdf-label)
