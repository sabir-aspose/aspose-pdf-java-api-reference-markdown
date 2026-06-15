---
title: "HighlightAnnotation"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents a highlight annotation that highlights a range of text in the document."
type: docs
url: "/java/com.aspose.pdf/highlightannotation/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/highlightannotation/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:57:56+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation), [com.aspose.pdf.TextMarkupAnnotation](../../com.aspose.pdf/textmarkupannotation)

```
public final class HighlightAnnotation extends TextMarkupAnnotation
```

Represents a highlight annotation that highlights a range of text in the document.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [HighlightAnnotation(Page page, Rectangle rect)](#HighlightAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Highlight annotation on the specified page. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |

### HighlightAnnotation(Page page, Rectangle rect) {#HighlightAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}

```
public HighlightAnnotation(Page page, Rectangle rect)
```

Creates new Highlight annotation on the specified page.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document’s page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}

```
public void accept(AnnotationSelector visitor)
```

Accepts visitor object to process the annotation.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

### getAnnotationType() {#getAnnotationType--}

```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType element
