---
sidebar_position: 2
toc_max_heading_level: 5
sidebar_label: 'Samples'
pagination_next: null
---

# Xamarin Forms SDK Samples

This page provides a list of samples available for the Scandit Data Capture SDK for Xamarin Forms. Each sample demonstrates a specific feature or use case of the SDK.

The repository with all the samples can be found [here](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master), and each individual sample is linked below.

## Barcode Scanning

### Single Scanning

#### Barcode Capture


##### [Single Scan](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master/BarcodeCaptureSimpleSample)

Simple sample showing how to use the Barcode Capture mode to scan a single barcode.

##### [Capture Views](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master/BarcodeCaptureViewsSample)

Demonstrates the various ways to best integrate the scanner into the UI of your app.

##### [Capture Settings](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master/BarcodeCaptureSettingsSample)

Demonstrates how you can adapt the barcode capture settings best to your needs and experiment with all the options.

##### [Rejection](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master/BarcodeCaptureRejectSample)

Sample that uses the camera to read a single QR code that starts with “09:” but ignores/rejects all other codes.

#### Pre-built Workflows

##### SparkScan

![SparkScan List Building](/img/samples/sparkscan_list_building.png)

###### [List Building](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master/ListBuildingSample)

Use SparkScan to populate a list of scanned barcodes.

##### Barcode Selection

![Barcode Selection](/img/samples/barcode_selection.png)

###### [Simple Selection](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master/BarcodeSelectionSimpleSample)

Simple sample showing how to use the Barcode Selection mode to select a barcode.

### Multi-Scanning

#### MatrixScan AR

Examples utilizing the low-level `BarcodeTracking` API.

##### [Simple Highlight](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master/MatrixScanSimpleSample)

Simple sample showing how to use MatrixScan to highlight barcodes in a frame.

##### [AR Bubbles](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master/MatrixScanBubblesSample)

Demonstrates more advanced use of MatrixScan by showing AR bubbles above the barcodes with the barcode data.

#### Pre-built Workflows

##### MatrixScan Count

![MatrixScan Count](/img/samples/ms_count.png)

###### [Batch Scanning](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master/MatrixScanCountSimpleSample)

Use MatrixScan to batch scan and count the number of barcodes in a frame.

## ID Scanning

![ID Scanning](/img/samples/id_scanning.png)

### ID Capture

#### [Simple ID Capture](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master/IdCaptureSimpleSample)

Simple sample showing how to use the ID Capture mode to scan an ID card.

#### [Extended ID Capture](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master/IdCaptureExtendedSample)

Sample showing how to use the ID Capture mode to scan an ID card with additional fields.

### ID Verification

#### [US Driver's License](https://github.com/Scandit/datacapture-xamarin-forms-samples/tree/master/USDLVerificationSample)

Sample showing how to use the ID Capture mode to verify a US driver's license.
