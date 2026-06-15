---
title: "SubPath"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents vector graphics object on the page."
type: docs
url: "/java/com.aspose.pdf.vector/subpath/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.vector/subpath/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:56:06+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.vector.GraphicElement](../../com.aspose.pdf.vector/graphicelement)

```
public final class SubPath extends GraphicElement
```

Represents vector graphics object on the page. Basically, vector graphics objects are represented by two groups of SubPaths. One of them is represented by a set of lines and curves. Others are presented as rectangles and can sometimes be confused. Usually it is a rectangular area that has a color, but very often this rectangle is placed at the beginning of the page and defines the entire space of the page in white. So you get the SubPath, but visually you only see the text on the page.

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getRectangle()](#getRectangle--) |  |

### getRectangle() {#getRectangle--}

```
public Rectangle getRectangle()
```

Gets the bounding rectangle of the [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement).

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
