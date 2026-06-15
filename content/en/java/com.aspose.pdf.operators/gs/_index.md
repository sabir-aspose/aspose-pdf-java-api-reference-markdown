---
title: "GS"
second_title: "Aspose.PDF for Java API Reference"
description: "Class representing gs operator set parameters from graphic state parameter dictionary."
type: docs
url: "/java/com.aspose.pdf.operators/gs/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.operators/gs/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:54:18+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)

```
public class GS extends Operator
```

Class representing gs operator (set parameters from graphic state parameter dictionary).

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [GS(int index, ICommand command)](#GS-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [GS(String name)](#GS-java.lang.String-) | Initializes gs operator. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets name of graphic state resource. |
| [setName(String value)](#setName-java.lang.String-) | Sets name of graphic state resource. |
| [toString()](#toString--) | Returns string represnetation of operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |

### GS(int index, ICommand command) {#GS-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}

```
public GS(int index, ICommand command)
```

Constructor for operator class.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### GS(String name) {#GS-java.lang.String-}

```
public GS(String name)
```

Initializes gs operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of graphic state. |

### getName() {#getName--}

```
public String getName()
```

Gets name of graphic state resource.

**Returns:**
java.lang.String - String value

### setName(String value) {#setName-java.lang.String-}

```
public void setName(String value)
```

Sets name of graphic state resource.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### toString() {#toString--}

```
public String toString()
```

Returns string represnetation of operator.

**Returns:**
java.lang.String - String representation of operator.

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}

```
public void accept(IOperatorSelector visitor)
```

Accepts visitor object to process operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |
