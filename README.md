# FIBONAX-ASCOM-Camera-Driver-Releases
Official download page for the FIBONAX ASCOM Camera Driver

This driver provides ASCOM camera support for supported FIBONAX UVC camera models, including:

- FIBONAX CAMERA
- FIBONAX Nova200

## Supported Software

The driver has been tested with:

- N.I.N.A via ASCOM
- SharpCap via ASCOM
- SharpCap via DirectShow/UVC
- AMCap via DirectShow/UVC

Note: SharpCap can use FIBONAX cameras in two ways:
1. DirectShow/UVC mode by selecting the camera device directly, such as `FIBONAX Nova200`.
2. ASCOM mode by selecting `ASCOM Camera Driver for FIBONAXFIBONAX CAMERA`.

The available controls and interface layout may differ depending on the selected connection mode.

## Download

Please download the latest installer from the Releases page:

https://github.com/FIBONAX-BETTER/FIBONAX-ASCOM-Camera-Driver-Releases/releases/latest

## Installation

1. Download `FIBONAX_ASCOM_Camera_Driver_Setup_v1.0.0.exe` from the latest release.
2. Close astronomy software such as N.I.N.A, SharpCap, and AMCap before installation.
3. Run the installer.
4. Open your astronomy software and select:

`ASCOM Camera Driver for FIBONAXFIBONAX CAMERA`

## Notes

This ASCOM driver bridges supported FIBONAX UVC cameras to ASCOM-compatible astronomy software.

For real-time preview and focusing, users may also use the camera directly through UVC/DirectShow in supported applications such as SharpCap or AMCap.
