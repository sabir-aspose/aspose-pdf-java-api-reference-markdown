---
title: "PolylineAnnotation"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents polyline annotation that is similar to polygon except that the first and last vertex are not implicitly connected."
type: docs
url: "/java/com.aspose.pdf/polylineannotation/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/polylineannotation/"
generated_from: "online-reference"
fetched_at: "2026-06-15T18:00:00+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation), [com.aspose.pdf.PolyAnnotation](../../com.aspose.pdf/polyannotation)

```
public final class PolylineAnnotation extends PolyAnnotation
```

Represents polyline annotation that is similar to polygon, except that the first and last vertex are not implicitly connected.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [PolylineAnnotation(Page page, Rectangle rect, Point[] vertices)](#PolylineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point---) | Creates new Polyline annotation on the specified page. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |

### PolylineAnnotation(Page page, Rectangle rect, Point[] vertices) {#PolylineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point---}

```
public PolylineAnnotation(Page page, Rectangle rect, Point[] vertices)
```

Creates new Polyline annotation on the specified page.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document’s page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |
| vertices | [Point[]](../../com.aspose.pdf/point) | An array of polygon vertices points. |

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
