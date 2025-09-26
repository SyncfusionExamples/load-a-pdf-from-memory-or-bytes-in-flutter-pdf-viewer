# Load a PDF document from memory or bytes in Flutter PDF Viewer

The [SfPdfViewer.memory](https://pub.dev/documentation/syncfusion_flutter_pdfviewer/latest/pdfviewer/SfPdfViewer/SfPdfViewer.memory.html) creates a widget that displays the PDF document obtained from the [`Uint8List`](https://api.flutter.dev/flutter/dart-typed_data/Uint8List-class.html). The following code example explains the same.

``` dart
@override
Widget build(BuildContext context) {
  return Scaffold(
      body: SfPdfViewer.memory(
              bytes));
}
```

## System requirements

https://help.syncfusion.com/flutter/system-requirements

## Clone the repository

* To clone the sample repository locally, open the command prompt in the desired location and execute the following command.

```sh

git clone https://github.com/SyncfusionExamples/load-a-pdf-from-memory-or-bytes-in-flutter-pdf-viewer.git

```

* Navigate to the project directory:

```sh
cd load-a-pdf-from-memory-or-bytes-in-flutter-pdf-viewer
```

To learn more about [SfPdfViewer](https://pub.dev/documentation/syncfusion_flutter_pdfviewer/latest/pdfviewer/SfPdfViewer-class.html) widget and its features, refer to this [documentation](https://help.syncfusion.com/flutter/pdf-viewer/overview) 
