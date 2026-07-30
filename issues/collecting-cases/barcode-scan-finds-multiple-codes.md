# Collecting cases: barcode scan finds multiple codes on one label

We are collecting cases where a shipping label contains multiple barcodes or QR codes, and it is unclear which one should be treated as the main tracking number.

中文说明：这个 issue 用来收集“一张面单上有多个条码，哪个才是主跟踪号”的案例。

## What we are trying to understand

Shipping labels may include:

- Main tracking number barcode
- Carrier routing barcode
- Order barcode
- Warehouse or picking barcode
- Return label barcode
- QR code or Data Matrix code

We want to improve how tools recommend the most likely tracking number while still showing all detected codes when needed.

## Please share

- Carrier or platform
- Barcode types detected, if known
- Which code is the real tracking number
- Whether the label includes order, warehouse, or return codes
- Whether the wrong code was recommended
- Whether showing all codes or only the recommended code is more useful

## Privacy note

Please mask customer information, tracking numbers, order numbers, and barcode images before sharing examples.

## Related tools

- Extract Tracking Numbers: https://www.autoshipflow.com/tools/extract-tracking-numbers
- Barcode & QR Scanner: https://www.autoshipflow.com/tools/barcode-scan
- Label Renamer: https://www.autoshipflow.com/tools/label-renamer
