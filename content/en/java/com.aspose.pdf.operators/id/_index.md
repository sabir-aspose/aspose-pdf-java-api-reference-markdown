---
title: "ID"
second_title: "Aspose.PDF for Java API Reference"
description: "Class representing ID operator Begin inline image data."
type: docs
url: "/java/com.aspose.pdf.operators/id/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.operators/id/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:54:19+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)

```
public class ID extends Operator
```

Class representing ID operator (Begin inline image data).

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [ID(int index, ICommand command)](#ID-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getCommandName()](#getCommandName--) |  |

### ID(int index, ICommand command) {#ID-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}

```
public ID(int index, ICommand command)
```

Constructor for operator class.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}

```
public void accept(IOperatorSelector visitor)
```

Accepts visitor object to process operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

### getCommandName() {#getCommandName--}

```
public String getCommandName()
```

Gets operator name.

**Returns:**
java.lang.String
