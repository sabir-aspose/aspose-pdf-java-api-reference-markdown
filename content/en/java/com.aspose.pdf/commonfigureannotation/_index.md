---
title: "CommonFigureAnnotation"
second_title: "Aspose.PDF for Java API Reference"
description: "Abstract class representing common figure annotation."
type: docs
url: "/java/com.aspose.pdf/commonfigureannotation/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/commonfigureannotation/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:56:53+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)

```
public abstract class CommonFigureAnnotation extends MarkupAnnotation
```

Abstract class representing common figure annotation.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [CommonFigureAnnotation(IDocument document)](#CommonFigureAnnotation-com.aspose.pdf.IDocument-) | Constructor for using in Generator. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getInteriorColor()](#getInteriorColor--) | Interior color with which to fill the annotation’s rectangle or ellipse. |
| [setInteriorColor(Color value)](#setInteriorColor-com.aspose.pdf.Color-) | Interior color with which to fill the annotation’s rectangle or ellipse. |
| [getFrame()](#getFrame--) | The rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and the actual boundaries of the underlying square or circle. |
| [setFrame(Rectangle value)](#setFrame-com.aspose.pdf.Rectangle-) | The rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and the actual boundaries of the underlying square or circle. |

### CommonFigureAnnotation(IDocument document) {#CommonFigureAnnotation-com.aspose.pdf.IDocument-}

```
public CommonFigureAnnotation(IDocument document)
```

Constructor for using in Generator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where annotation will be placed. |

### getInteriorColor() {#getInteriorColor--}

```
public Color getInteriorColor()
```

Interior color with which to fill the annotation’s rectangle or ellipse.

**Returns:**
[Color](../../com.aspose.pdf/color) - interior color with which to fill the annotation’s rectangle or ellipse.

### setInteriorColor(Color value) {#setInteriorColor-com.aspose.pdf.Color-}

```
public void setInteriorColor(Color value)
```

Interior color with which to fill the annotation’s rectangle or ellipse.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | interior color |

### getFrame() {#getFrame--}

```
public Rectangle getFrame()
```

The rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and the actual boundaries of the underlying square or circle.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - rectangle frame

### setFrame(Rectangle value) {#setFrame-com.aspose.pdf.Rectangle-}

```
public void setFrame(Rectangle value)
```

The rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and the actual boundaries of the underlying square or circle.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | rectangle frame |
