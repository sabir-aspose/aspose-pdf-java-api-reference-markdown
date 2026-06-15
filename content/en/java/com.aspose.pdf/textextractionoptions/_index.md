---
title: "TextExtractionOptions"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents text extraction options"
type: docs
url: "/java/com.aspose.pdf/textextractionoptions/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/textextractionoptions/"
generated_from: "online-reference"
fetched_at: "2026-06-15T18:01:20+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)

```
public final class TextExtractionOptions extends TextOptions
```

Represents text extraction options

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [TextExtractionOptions(int formattingMode)](#TextExtractionOptions-int-) | Initializes new instance of the TextExtractionOptions object for the specified text formatting mode. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getFormattingMode()](#getFormattingMode--) | Gets formatting mode. |
| [setFormattingMode(int value)](#setFormattingMode-int-) | Sets formatting mode. |
| [getScaleFactor()](#getScaleFactor--) | Gets factor that will be applied to scale font size during extraction in pure mode. |
| [setScaleFactor(double value)](#setScaleFactor-double-) | Sets factor that will be applied to scale font size during extraction in pure mode. |

### TextExtractionOptions(int formattingMode) {#TextExtractionOptions-int-}

```
public TextExtractionOptions(int formattingMode)
```

Initializes new instance of the TextExtractionOptions object for the specified text formatting mode.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| formattingMode | int | Text formatting mode value. |

### getFormattingMode() {#getFormattingMode--}

```
public int getFormattingMode()
```

Gets formatting mode.

**Returns:**
int - TextFormattingMode value

### setFormattingMode(int value) {#setFormattingMode-int-}

```
public void setFormattingMode(int value)
```

Sets formatting mode.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TextFormattingMode value |

### getScaleFactor() {#getScaleFactor--}

```
public double getScaleFactor()
```

Gets factor that will be applied to scale font size during extraction in pure mode. Setting of less value leads to more spaces in the extracted text. Default value is 1 - no scaling; Setting value to zero allows algorithm choose scaling automatically.

**Returns:**
double - double value

### setScaleFactor(double value) {#setScaleFactor-double-}

```
public void setScaleFactor(double value)
```

Sets factor that will be applied to scale font size during extraction in pure mode. Setting of less value leads to more spaces in the extracted text (from 1 to 10). Default value is 1 - no scaling; Setting value to zero allows algorithm choose scaling automatically.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |
