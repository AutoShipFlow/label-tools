# Rename Shipping Label Files by Tracking Number

[简体中文](../../../zh-CN/shipping-workflows/rename-labels-by-tracking-number.md)

## Problem

Warehouses and operations teams often receive one merged shipping label PDF. To archive labels, upload files to another system, or search labels later, each page needs to become a separate file named by its tracking number.

## Common Causes

- Platforms export many labels into one merged PDF.
- File names such as `labels.pdf` or `download.pdf` do not help warehouse staff find a specific shipment.
- Manual splitting and renaming takes too long for large batches.
- Tracking numbers are available on each label but need barcode recognition to extract reliably.

## How to Fix It

Use [Label Renamer](https://www.autoshipflow.com/tools/label-renamer):

1. Upload the merged shipping label PDF.
2. Scan each page for tracking numbers.
3. Review the filename preview.
4. Download a ZIP of single-label files named by tracking number.

## What the Tool Can and Cannot Fix

The tool can split a merged label PDF and name each page by the detected tracking number.

It cannot guarantee perfect naming when a label has multiple competing barcodes, missing tracking numbers, or low-quality scans. Review the preview before downloading and importing into another system.

## Related Tools

- [Label Renamer](https://www.autoshipflow.com/tools/label-renamer)
- [Split Label PDF](https://www.autoshipflow.com/tools/split-label)
- [Extract Tracking Numbers](https://www.autoshipflow.com/tools/extract-tracking-numbers)
