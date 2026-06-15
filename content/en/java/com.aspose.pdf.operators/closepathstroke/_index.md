---
title: "ClosePathStroke"
second_title: "Aspose.PDF for Java API Reference"
description: "Class representing s operator Close and stroke path."
type: docs
url: "/java/com.aspose.pdf.operators/closepathstroke/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.operators/closepathstroke/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:54:08+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)

```
public class ClosePathStroke extends Operator
```

Class representing s operator (Close and stroke path).

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [ClosePathStroke(int index, ICommand command)](#ClosePathStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [ClosePathStroke()](#ClosePathStroke--) | Initializes operator. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of the operator. |

### ClosePathStroke(int index, ICommand command) {#ClosePathStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}

```
public ClosePathStroke(int index, ICommand command)
```

Constructor for operator class.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### ClosePathStroke() {#ClosePathStroke--}

```
public ClosePathStroke()
```

Initializes operator.

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}

```
public void accept(IOperatorSelector visitor)
```

Accepts visitor object to process operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

### toString() {#toString--}

```
public String toString()
```

Returns text representation of the operator.

**Returns:**
java.lang.String - Text representation of the operator.
