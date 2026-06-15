---
title: "EI"
second_title: "Aspose.PDF for Java API Reference"
description: "Class representing EI operator End inline image object."
type: docs
url: "/java/com.aspose.pdf.operators/ei/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.operators/ei/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:54:12+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)

```
public class EI extends Operator
```

Class representing EI operator (End inline image object).

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [EI()](#EI--) | Initializes operator. |
| [EI(int index, ICommand command)](#EI-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Translates command and parameters into string representation. |

### EI() {#EI--}

```
public EI()
```

Initializes operator.

### EI(int index, ICommand command) {#EI-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}

```
public EI(int index, ICommand command)
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

### toString() {#toString--}

```
public String toString()
```

Translates command and parameters into string representation.

**Returns:**
java.lang.String - Operator text
