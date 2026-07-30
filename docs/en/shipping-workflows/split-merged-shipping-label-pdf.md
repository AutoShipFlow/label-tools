# Split Merged Shipping Label PDFs

[简体中文](../../../zh-CN/shipping-workflows/split-merged-shipping-label-pdf.md)

## Problem

A platform exports many shipping labels as one multi-page PDF. You need one label per file for printing, sharing, warehouse assignment, or manual review.

## Common Causes

- Order platforms and shipping systems often batch labels into one PDF.
- Some warehouse workflows require one label file per shipment.
- A merged PDF is hard to send, reprint, or review page by page.
- You may not need tracking-number filenames, only separate page files.

## How to Fix It

Use [Split Label PDF](https://www.autoshipflow.com/tools/split-label):

1. Upload the merged shipping label PDF.
2. Split the PDF into one page per file.
3. Download the ZIP package.
4. Use Label Renamer instead if you need filenames based on tracking numbers.

## What the Tool Can and Cannot Fix

The tool can split a merged PDF into separate single-page label files.

It does not rename files by tracking number. If you need tracking-number filenames, use Label Renamer.

## Related Tools

- [Split Label PDF](https://www.autoshipflow.com/tools/split-label)
- [Label Renamer](https://www.autoshipflow.com/tools/label-renamer)
- [Extract Tracking Numbers](https://www.autoshipflow.com/tools/extract-tracking-numbers)
