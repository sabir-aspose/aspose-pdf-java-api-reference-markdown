---
title: "TextOperator"
second_title: "Aspose.PDF for Java API Reference"
description: "Abstract base class for text-related operators TJ Tj Tm BT ET etc."
type: docs
url: "/java/com.aspose.pdf.operators/textoperator/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.operators/textoperator/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:54:47+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)

```
public abstract class TextOperator extends Operator
```

Abstract base class for text-related operators (TJ, Tj, Tm, BT, ET, etc).

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [TextOperator()](#TextOperator--) | Constructor for new operator. |
| [TextOperator(TextProperties textProperties)](#TextOperator-com.aspose.pdf.facades.TextProperties-) | Text operator which accepts text properties. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |

### TextOperator() {#TextOperator--}

```
public TextOperator()
```

Constructor for new operator.

### TextOperator(TextProperties textProperties) {#TextOperator-com.aspose.pdf.facades.TextProperties-}

```
public TextOperator(TextProperties textProperties)
```

Text operator which accepts text properties.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| textProperties | [TextProperties](../../com.aspose.pdf.facades/textproperties) | Text properties. |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}

```
public void accept(IOperatorSelector visitor)
```

Accepts visitor object to process operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |
