---
title: "PdfJavaScriptStripper"
second_title: "Aspose.PDF for Java API Reference"
description: "Class for removing all Java Script code."
type: docs
url: "/java/com.aspose.pdf.facades/pdfjavascriptstripper/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.facades/pdfjavascriptstripper/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:53:41+00:00"
---
**Inheritance:**
java.lang.Object

```
public final class PdfJavaScriptStripper
```

Class for removing all Java Script code.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [PdfJavaScriptStripper()](#PdfJavaScriptStripper--) |  |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [strip(String inputFile, String outputFile)](#strip-java.lang.String-java.lang.String-) | Remove Java Script from document. |
| [strip(InputStream inStream, OutputStream outStream)](#strip-java.io.InputStream-java.io.OutputStream-) | Remove Java Script from the document. |

### PdfJavaScriptStripper() {#PdfJavaScriptStripper--}

```
public PdfJavaScriptStripper()
```

### strip(String inputFile, String outputFile) {#strip-java.lang.String-java.lang.String-}

```
public boolean strip(String inputFile, String outputFile)
```

Remove Java Script from document.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | File containig the document. |
| outputFile | java.lang.String | File where document will be stored. |

**Returns:**
boolean - true if JavaScript was stripped successfully.

### strip(InputStream inStream, OutputStream outStream) {#strip-java.io.InputStream-java.io.OutputStream-}

```
public boolean strip(InputStream inStream, OutputStream outStream)
```

Remove Java Script from the document.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| inStream | java.io.InputStream | Stream containing document. |
| outStream | java.io.OutputStream | Stream where the document will be stored. |

**Returns:**
boolean - true if JavaScript was stripped successfully.
