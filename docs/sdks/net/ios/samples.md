---
sidebar_position: 2
toc_max_heading_level: 5
sidebar_label: 'Samples'
pagination_next: null
---

# .NET iOS SDK Samples

This page provides a list of samples available for the Scandit Data Capture SDK for .NET iOS. Each sample demonstrates a specific feature or use case of the SDK.

The repository with all the samples can be found [here](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios), and each individual sample is linked below.

:::tip
The samples here are also available for [MAUI](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/maui).
:::

## Barcode Scanning

### Single Scanning

#### Barcode Capture


##### [Single Scan](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/BarcodeCaptureSimpleSample)

Simple sample showing how to use the Barcode Capture mode to scan a single barcode.

##### [Capture Views](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/BarcodeCaptureViewsSample)

Demonstrates the various ways to best integrate the scanner into the UI of your app.

##### [Rejection](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/BarcodeCaptureRejectSample)

Sample that uses the camera to read a single QR code that starts with “09:” but ignores/rejects all other codes.

#### Pre-built Workflows

##### SparkScan

![SparkScan List Building](/img/samples/sparkscan_list_building.png)

###### [List Building](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/ListBuildingSample)

Use SparkScan to populate a list of scanned barcodes.

##### Barcode Selection

![Barcode Selection](/img/samples/barcode_selection.png)

###### [Simple Selection](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/BarcodeSelectionSimpleSample)

Simple sample showing how to use the Barcode Selection mode to select a barcode.

### Multi-Scanning

#### MatrixScan AR

Examples utilizing the low-level `BarcodeTracking` API.

##### [Simple Highlight](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/MatrixScanSimpleSample)

Simple sample showing how to use MatrixScan to highlight barcodes in a frame.

##### [AR Bubbles](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/MatrixScanBubblesSample)

Demonstrates more advanced use of MatrixScan by showing AR bubbles above the barcodes with the barcode data.

##### [Rejection](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/MatrixScanRejectSample)

Use custom conditions to highlight and scan only the barcodes that meet the specified criteria.

#### Pre-built Workflows

##### MatrixScan Count

![MatrixScan Count](/img/samples/ms_count.png)

###### [Batch Scanning](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/MatrixScanCountSimpleSample)

Use MatrixScan to batch scan and count the number of barcodes in a frame.

##### MatrixScan Find

![MatrixScan Find](/img/samples/ms_find_android.png)

###### [Search and Find](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/SearchAndFindSample)

Use barcode capture to define search criteria by scanning items, and MatrixScan Find can then be launched to find the pre-defined item.

## ID Scanning

![ID Scanning](/img/samples/id_scanning.png)

### ID Capture

#### [Simple ID Capture](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/IdCaptureSimpleSample)

Simple sample showing how to use the ID Capture mode to scan an ID card.

#### [Extended ID Capture](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/IdCaptureExtendedSample)

Sample showing how to use the ID Capture mode to scan an ID card with additional fields.

### ID Verification

#### [US Driver's License](https://github.com/Scandit/datacapture-dotnet-samples/tree/master/ios/USDLVerificationSample)

Sample showing how to use the ID Capture mode to verify a US driver's license.
