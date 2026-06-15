---
title: "ILSTextElement"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents a base class for inline-level text structure elements in logical structure."
type: docs
url: "/java/com.aspose.pdf.tagged.logicalstructure.elements.ils/ilstextelement/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.tagged.logicalstructure.elements.ils/ilstextelement/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:55:23+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/ilselement)

**All Implemented Interfaces:**
[com.aspose.pdf.tagged.logicalstructure.elements.ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement)

```
public abstract class ILSTextElement extends ILSElement implements ITextElement
```

Represents a base class for inline-level text structure elements in logical structure.

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getStructureTextState()](#getStructureTextState--) | Gets StructureTextState object for current element. |
| [setText(String text)](#setText-java.lang.String-) | Appends text content to current text element. |

### getStructureTextState() {#getStructureTextState--}

```
public final StructureTextState getStructureTextState()
```

Gets StructureTextState object for current element.

Value: StructureTextState object for current element.

**Returns:**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate)

### setText(String text) {#setText-java.lang.String-}

```
public final void setText(String text)
```

Appends text content to current text element.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content. |
