---
title: "PageDevice"
second_title: "Aspose.PDF for Java API Reference"
description: "Abstract class for all devices which is used to process certain page the pdf document."
type: docs
url: "/java/com.aspose.pdf.devices/pagedevice/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/pagedevice/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:52:41+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device)

```
public abstract class PageDevice extends Device
```

Abstract class for all devices which is used to process certain page the pdf document.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [PageDevice()](#PageDevice--) |  |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Performs some operation on the given page, e.g. |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Performs some operation on the given page, e.g. |
| [process(Page page, String outputFileName)](#process-com.aspose.pdf.Page-java.lang.String-) | Performs some operation on the given page and saves results into the file. |
| [process(Page page, System.Drawing.Graphics gr)](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | Renders page on the graphics |

### PageDevice() {#PageDevice--}

```
public PageDevice()
```

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}

```
public abstract void processInternal(Page page, System.IO.Stream output)
```

Performs some operation on the given page, e.g. converts page into graphic image.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to process. |
| output | com.aspose.ms.System.IO.Stream | This stream contains the results of processing. |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}

```
public void process(Page page, OutputStream output)
```

Performs some operation on the given page, e.g. converts page into graphic image.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to process. |
| output | java.io.OutputStream | This stream contains the results of processing. |

### process(Page page, String outputFileName) {#process-com.aspose.pdf.Page-java.lang.String-}

```
public void process(Page page, String outputFileName)
```

Performs some operation on the given page and saves results into the file.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to process. |
| outputFileName | java.lang.String | This file contains the results of processing. |

### process(Page page, System.Drawing.Graphics gr) {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}

```
public void process(Page page, System.Drawing.Graphics gr)
```

Renders page on the graphics

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object |
| gr | com.aspose.ms.System.Drawing.Graphics | internal object |
