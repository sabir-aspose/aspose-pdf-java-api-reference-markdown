---
title: "GRestore"
second_title: "Aspose.PDF for Java API Reference"
description: "Class representing Q operator restore graphics state."
type: docs
url: "/java/com.aspose.pdf.operators/grestore/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.operators/grestore/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:54:18+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)

```
public class GRestore extends Operator
```

Class representing Q operator (restore graphics state).

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [GRestore(int index, ICommand command)](#GRestore-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [GRestore()](#GRestore--) | Constructor for Q operator. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [toString()](#toString--) | Returns text of the operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |

### GRestore(int index, ICommand command) {#GRestore-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}

```
public GRestore(int index, ICommand command)
```

Constructor for operator class.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### GRestore() {#GRestore--}

```
public GRestore()
```

Constructor for Q operator.

### toString() {#toString--}

```
public String toString()
```

Returns text of the operator.

**Returns:**
java.lang.String - Text representation of the operator.

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}

```
public void accept(IOperatorSelector visitor)
```

Accepts visitor object to process operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |
