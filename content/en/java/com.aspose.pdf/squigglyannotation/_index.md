---
title: "SquigglyAnnotation"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents the squiggly annotation that appears as a jagged underline in the text of a document."
type: docs
url: "/java/com.aspose.pdf/squigglyannotation/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/squigglyannotation/"
generated_from: "online-reference"
fetched_at: "2026-06-15T18:00:51+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation), [com.aspose.pdf.TextMarkupAnnotation](../../com.aspose.pdf/textmarkupannotation)

```
public final class SquigglyAnnotation extends TextMarkupAnnotation
```

Represents the squiggly annotation that appears as a jagged underline in the text of a document.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [SquigglyAnnotation(Page page, Rectangle rect)](#SquigglyAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Squiggly annotation on the specified page. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |

### SquigglyAnnotation(Page page, Rectangle rect) {#SquigglyAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}

```
public SquigglyAnnotation(Page page, Rectangle rect)
```

Creates new Squiggly annotation on the specified page.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document’s page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |

### getAnnotationType() {#getAnnotationType--}

```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType element

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}

```
public void accept(AnnotationSelector visitor)
```

Accepts visitor object to process the annotation.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |
