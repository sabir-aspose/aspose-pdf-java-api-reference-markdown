---
title: "ShFill"
second_title: "Aspose.PDF for Java API Reference"
description: "Class representing sh operator paint area with shading pattern."
type: docs
url: "/java/com.aspose.pdf.operators/shfill/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.operators/shfill/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:54:46+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)

```
public class ShFill extends Operator
```

Class representing sh operator (paint area with shading pattern).

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [ShFill()](#ShFill--) | Initializes operator. |
| [ShFill(int index, ICommand command)](#ShFill-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [ShFill(String shadingName)](#ShFill-java.lang.String-) | Initializes operator. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the shading name. |
| [setName(String value)](#setName-java.lang.String-) | Sets the shading name. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |

### ShFill() {#ShFill--}

```
public ShFill()
```

Initializes operator.

### ShFill(int index, ICommand command) {#ShFill-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}

```
public ShFill(int index, ICommand command)
```

Constructor for operator class.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### ShFill(String shadingName) {#ShFill-java.lang.String-}

```
public ShFill(String shadingName)
```

Initializes operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| shadingName | java.lang.String | String Shading name. |

### getName() {#getName--}

```
public String getName()
```

Gets the shading name.

**Returns:**
java.lang.String - String value

### setName(String value) {#setName-java.lang.String-}

```
public void setName(String value)
```

Sets the shading name.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}

```
public void accept(IOperatorSelector visitor)
```

Accepts visitor object to process operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |
