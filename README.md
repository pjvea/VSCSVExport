VSCSVExport
============


VSCSVExport is a simple Swift class that generates a CSV file, opens a document preview of the file and allows for sharing of the file.


Installation
============


Add `VSCSVExport.swift` to your project.


Usage
=====

Use the method `exportCSV` to generates a CSV file and open it in a document previewer.

```
VSCSVExport().exportCSV(fileName: "TestCSVFileName", columnTitles: ["Title", "Other Title"], dataByRow: [["Apple", "iPhone X"], ["Google", "Pixel XL 2"]], presentingVC: self)
```

Screenshot
==========

![CSV Export Screenshot](/CSVExportScreenshot.png)