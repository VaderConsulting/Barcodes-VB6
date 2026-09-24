# Barcodes

VB6 barcode toolkit: Access MDB barcode-to-asset interface (`Barcodes.exe`), keyboard wedge apps, and barcode ActiveX/picture controls across several subprojects. Distinct from later .NET barcode work. Open any of the listed `.vbp` files in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** ActiveX OCX, WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Barcodes` (`Barcodes.vbp`) | VB6 | WinForms exe | Barcode wedge to Access MDB lookup |
| `EmpiredBarcodeApp` (`Keyboard Barcode (v2)/EmpiredBarcodeApp.vbp`) | VB6 | WinForms exe | EmpiredBarcodeApp |
| `BCode` (`Barcodes/Projekt1.vbp`) | VB6 | WinForms exe | BCode |
| `BarPic` (`Barcode Picture/Barpic.vbp`) | VB6 | ActiveX OCX | BarPic |
| `Barcode` (`Barcode Control/Barcode.vbp`) | VB6 | ActiveX OCX | Barcode |
| `Project1` (`Barcode/Barcode.vbp`) | VB6 | WinForms exe | Project1 |
| `Barcodes` (`Keyboard IO (v1)/Barcodes.vbp`) | VB6 | WinForms exe | Barcodes |
| `Project1` (`Andy/Project1.vbp`) | VB6 | WinForms exe | Project1 |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Barcodes.vbp`
- `Keyboard Barcode (v2)/EmpiredBarcodeApp.vbp`
- `Barcodes/Projekt1.vbp`
- `Barcode Picture/Barpic.vbp`
- `Barcode Control/Barcode.vbp`
- `Barcode/Barcode.vbp`
- `Keyboard IO (v1)/Barcodes.vbp`
- `Andy/Project1.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `COMCT232.OCX`
  - `MSADODC.OCX`
  - `MSCOMCTL.OCX`
  - `MSCOMM32.OCX`
  - `akled.ocx`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Barcodes`.
Company names in project files: Chips, Bits and Bytes, F@t_F|sh.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
