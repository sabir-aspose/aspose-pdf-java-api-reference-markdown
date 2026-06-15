---
title: "XmlLoadOptions"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents options for loading/importing XML file into pdf document."
type: docs
url: "/java/com.aspose.pdf/xmlloadoptions/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/xmlloadoptions/"
generated_from: "online-reference"
fetched_at: "2026-06-15T18:01:55+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)

```
public class XmlLoadOptions extends LoadOptions
```

Represents options for loading/importing XML file into pdf document.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [XmlLoadOptions()](#XmlLoadOptions--) | Creates XmlLoadOptions object without xsl data. |
| [XmlLoadOptions(String xslFile)](#XmlLoadOptions-java.lang.String-) | Creates XmlLoadOptions object with xsl data. |
| [XmlLoadOptions(InputStream xslStream)](#XmlLoadOptions-java.io.InputStream-) | Creates XmlLoadOptions object with xsl data. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getXslStream()](#getXslStream--) | Gets xsl data for converting xml into pdf document. |
| [close()](#close--) | Close instance |

### XmlLoadOptions() {#XmlLoadOptions--}

```
public XmlLoadOptions()
```

Creates XmlLoadOptions object without xsl data.

### XmlLoadOptions(String xslFile) {#XmlLoadOptions-java.lang.String-}

```
public XmlLoadOptions(String xslFile)
```

Creates XmlLoadOptions object with xsl data.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| xslFile | java.lang.String | String Xsl file to convert xml document into pdf document. |

### XmlLoadOptions(InputStream xslStream) {#XmlLoadOptions-java.io.InputStream-}

```
public XmlLoadOptions(InputStream xslStream)
```

Creates XmlLoadOptions object with xsl data.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| xslStream | java.io.InputStream | InputStream Xsl stream to convert xml document into pdf document. |

### getXslStream() {#getXslStream--}

```
public InputStream getXslStream()
```

Gets xsl data for converting xml into pdf document.

**Returns:**
java.io.InputStream - InputStream

### close() {#close--}

```
public void close()
```

Close instance
