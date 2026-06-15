---
title: "WarningCallback"
second_title: "Aspose.PDF for Java API Reference"
description: "Interface for users callback mechanism support."
type: docs
url: "/java/com.aspose.pdf/warningcallback/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/warningcallback/"
generated_from: "online-reference"
fetched_at: "2026-06-15T18:01:44+00:00"
---
**Inheritance:**
java.lang.Object

```
public abstract class WarningCallback
```

Interface for user’s callback mechanism support.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [WarningCallback()](#WarningCallback--) |  |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [warning(WarningInfo warning)](#warning-com.aspose.pdf.WarningInfo-) | The callback method for some program notifications. |

### WarningCallback() {#WarningCallback--}

```
public WarningCallback()
```

### warning(WarningInfo warning) {#warning-com.aspose.pdf.WarningInfo-}

```
public abstract WarningCallback.ReturnAction warning(WarningInfo warning)
```

The callback method for some program notifications.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| warning | [WarningInfo](../../com.aspose.pdf/warninginfo) | the warning information for some happened warning |

**Returns:**
[ReturnAction](../../com.aspose.pdf/returnaction) - the result of further program workflow
