---
title: "BT"
second_title: "Aspose.PDF for Java API Reference"
description: "Class representing BT operator Begin of text block."
type: docs
url: "/java/com.aspose.pdf.operators/bt/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.operators/bt/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:54:05+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.BlockTextOperator](../../com.aspose.pdf.operators/blocktextoperator)

```
public class BT extends BlockTextOperator
```

Class representing BT operator (Begin of text block).

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [BT(int index, ICommand command)](#BT-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [BT()](#BT--) | Constructor for writing program. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Produces text code of operator. |
| [toCommand()](#toCommand--) |  |

### BT(int index, ICommand command) {#BT-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}

```
public BT(int index, ICommand command)
```

Constructor for operator class.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### BT() {#BT--}

```
public BT()
```

Constructor for writing program.

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

Produces text code of operator.

**Returns:**
java.lang.String - Text representation of operator.

### toCommand() {#toCommand--}

```
public ICommand toCommand()
```

**Returns:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand)
