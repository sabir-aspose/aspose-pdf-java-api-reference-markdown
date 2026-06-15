---
title: "EMC"
second_title: "Aspose.PDF for Java API Reference"
description: "Clsss representing EMC oeprator End of marked-content sequence."
type: docs
url: "/java/com.aspose.pdf.operators/emc/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.operators/emc/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:54:13+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)

```
public class EMC extends Operator
```

Clsss representing EMC oeprator (End of marked-content sequence).

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [EMC(int index, ICommand command)](#EMC-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [EMC()](#EMC--) | Constructor for writing program. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |

### EMC(int index, ICommand command) {#EMC-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}

```
public EMC(int index, ICommand command)
```

Constructor for operator class.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### EMC() {#EMC--}

```
public EMC()
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

Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of the operator.
