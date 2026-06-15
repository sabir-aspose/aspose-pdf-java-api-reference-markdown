---
title: "SetTextMatrix"
second_title: "Aspose.PDF for Java API Reference"
description: "Class representig Tm operator set text matrix."
type: docs
url: "/java/com.aspose.pdf.operators/settextmatrix/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.operators/settextmatrix/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:54:44+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextPlaceOperator](../../com.aspose.pdf.operators/textplaceoperator)

```
public class SetTextMatrix extends TextPlaceOperator
```

Class representig Tm operator (set text matrix).

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [SetTextMatrix(int index, ICommand command)](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Initializes operator. |
| [SetTextMatrix(double a, double b, double c, double d, double e, double f)](#SetTextMatrix-double-double-double-double-double-double-) | Initializes operator. |
| [SetTextMatrix(Matrix m)](#SetTextMatrix-com.aspose.pdf.Matrix-) | Initializes operator by matrix. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getMatrix()](#getMatrix--) | Matrix argument of the operator. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.pdf.Matrix-) | Matrix argument of the operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |

### SetTextMatrix(int index, ICommand command) {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}

```
public SetTextMatrix(int index, ICommand command)
```

Initializes operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetTextMatrix(double a, double b, double c, double d, double e, double f) {#SetTextMatrix-double-double-double-double-double-double-}

```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

Initializes operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| a | double | A coefficient |
| b | double | B coefficient |
| c | double | C coefficient |
| d | double | D coefficient |
| e | double | E coefficient |
| f | double | F coefficient |

### SetTextMatrix(Matrix m) {#SetTextMatrix-com.aspose.pdf.Matrix-}

```
public SetTextMatrix(Matrix m)
```

Initializes operator by matrix.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| m | [Matrix](../../com.aspose.pdf/matrix) | Transfomation matrix. |

### getMatrix() {#getMatrix--}

```
public Matrix getMatrix()
```

Matrix argument of the operator.

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Matrix object

### setMatrix(Matrix value) {#setMatrix-com.aspose.pdf.Matrix-}

```
public void setMatrix(Matrix value)
```

Matrix argument of the operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.pdf/matrix) | Matrix object |

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
java.lang.String - Text representation of operator.
