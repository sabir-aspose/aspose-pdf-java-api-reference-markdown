---
title: "MoveTextPositionSetLeading"
second_title: "Aspose.PDF for Java API Reference"
description: "Class representing TD operator move position and set leading."
type: docs
url: "/java/com.aspose.pdf.operators/movetextpositionsetleading/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.operators/movetextpositionsetleading/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:54:22+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextPlaceOperator](../../com.aspose.pdf.operators/textplaceoperator)

```
public class MoveTextPositionSetLeading extends TextPlaceOperator
```

Class representing TD operator (move position and set leading).

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [MoveTextPositionSetLeading(int index, ICommand command)](#MoveTextPositionSetLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [MoveTextPositionSetLeading(double x, double y)](#MoveTextPositionSetLeading-double-double-) | Initializes operator. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getX()](#getX--) | X coordinate of text position. |
| [setX(double value)](#setX-double-) | X coordinate of text position. |
| [getY()](#getY--) | Y coordinate of text position. |
| [setY(double value)](#setY-double-) | Y coordinate of text position. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |

### MoveTextPositionSetLeading(int index, ICommand command) {#MoveTextPositionSetLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}

```
public MoveTextPositionSetLeading(int index, ICommand command)
```

Constructor for operator class.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### MoveTextPositionSetLeading(double x, double y) {#MoveTextPositionSetLeading-double-double-}

```
public MoveTextPositionSetLeading(double x, double y)
```

Initializes operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| x | double | X coordinate of text position. |
| y | double | Y coordinate of text position. |

### getX() {#getX--}

```
public double getX()
```

X coordinate of text position.

**Returns:**
double - double value

### setX(double value) {#setX-double-}

```
public void setX(double value)
```

X coordinate of text position.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getY() {#getY--}

```
public double getY()
```

Y coordinate of text position.

**Returns:**
double - double value

### setY(double value) {#setY-double-}

```
public void setY(double value)
```

Y coordinate of text position.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}

```
public void accept(IOperatorSelector visitor)
```

Accepts visitor object to process operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |
