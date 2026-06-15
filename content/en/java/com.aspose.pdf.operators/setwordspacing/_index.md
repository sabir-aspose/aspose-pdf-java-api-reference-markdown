---
title: "SetWordSpacing"
second_title: "Aspose.PDF for Java API Reference"
description: "Class representing Tw operator set word spacing."
type: docs
url: "/java/com.aspose.pdf.operators/setwordspacing/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.operators/setwordspacing/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:54:45+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextStateOperator](../../com.aspose.pdf.operators/textstateoperator)

```
public class SetWordSpacing extends TextStateOperator
```

Class representing Tw operator (set word spacing).

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [SetWordSpacing(int index, ICommand command)](#SetWordSpacing-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
| [SetWordSpacing(double wordSpacing)](#SetWordSpacing-double-) | Initializes operator. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getWordSpacing()](#getWordSpacing--) | Gets the word spacing. |
| [setWordSpacing(double value)](#setWordSpacing-double-) | Sets the word spacing. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |

### SetWordSpacing(int index, ICommand command) {#SetWordSpacing-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}

```
public SetWordSpacing(int index, ICommand command)
```

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

### SetWordSpacing(double wordSpacing) {#SetWordSpacing-double-}

```
public SetWordSpacing(double wordSpacing)
```

Initializes operator.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| wordSpacing | double | Word spacing. |

### getWordSpacing() {#getWordSpacing--}

```
public double getWordSpacing()
```

Gets the word spacing.

**Returns:**
double - double value

### setWordSpacing(double value) {#setWordSpacing-double-}

```
public void setWordSpacing(double value)
```

Sets the word spacing.

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
