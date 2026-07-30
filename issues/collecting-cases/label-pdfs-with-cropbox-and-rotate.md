# Collecting cases: label PDFs with CropBox and Rotate metadata

We are collecting label PDFs where the visible page size or orientation differs from the raw PDF page data because of CropBox, MediaBox, or Rotate metadata.

中文说明：这个 issue 用来收集包含 CropBox / Rotate 的特殊 PDF 标签案例。

## What we are trying to understand

Some PDF tools read the raw MediaBox size, while PDF viewers show the visual page after CropBox and Rotate are applied. This can cause previews or processed output to look rotated, cropped incorrectly, or placed in the wrong area.

We want to understand:

- Which platforms or carriers generate these PDFs
- Whether the file is visually portrait but raw landscape
- Whether CropBox differs from MediaBox
- Whether Rotate is 90 or 270 degrees
- Which tools handle the visual orientation correctly

## Please share

- Carrier or platform that generated the PDF
- Raw page size, CropBox, Rotate, or visual size if known
- Whether the label looks portrait or landscape in a normal PDF viewer
- What happens after resizing, cropping, or printing
- Whether the problem affects preview only or the exported PDF too

## Privacy note

Please do not upload real customer labels unless all private data is removed.

## Related tools

- Label Printing AI: https://www.autoshipflow.com/tools/label-printing-ai
- Crop Label: https://www.autoshipflow.com/tools/crop-label
- PDF Label Resizer: https://www.autoshipflow.com/tools/pdf-resize
