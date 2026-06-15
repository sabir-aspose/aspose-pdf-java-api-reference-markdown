---
title: "Opi"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents The Open Prepress Interface OPI is a mechanism for creating low-resolution placeholders or proxies for such high-resolution images."
type: docs
url: "/java/com.aspose.pdf/opi/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/opi/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:59:14+00:00"
---
**Inheritance:**
java.lang.Object

```
public final class Opi
```

Represents The Open Prepress Interface (OPI) is a mechanism for creating low-resolution placeholders, or proxies, for such high-resolution images.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [Opi(XForm xform)](#Opi-com.aspose.pdf.XForm-) | The constructor. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) | Gets the version of OPI to which this dictionary refers. |
| [getFileSpecification()](#getFileSpecification--) | Gets the external file containing the low- resolution proxy image. |
| [getPosition()](#getPosition--) | Gets an array of eight numbers of the form specifying the location on the page of the cropped image. |

### Opi(XForm xform) {#Opi-com.aspose.pdf.XForm-}

```
public Opi(XForm xform)
```

The constructor.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| xform | [XForm](../../com.aspose.pdf/xform) | Xform object. |

### getVersion() {#getVersion--}

```
public String getVersion()
```

Gets the version of OPI to which this dictionary refers.

**Returns:**
java.lang.String - String object

### getFileSpecification() {#getFileSpecification--}

```
public String getFileSpecification()
```

Gets the external file containing the low- resolution proxy image.

**Returns:**
java.lang.String - String object

### getPosition() {#getPosition--}

```
public double[] getPosition()
```

Gets an array of eight numbers of the form specifying the location on the page of the cropped image.

**Returns:**
double[] - double array
