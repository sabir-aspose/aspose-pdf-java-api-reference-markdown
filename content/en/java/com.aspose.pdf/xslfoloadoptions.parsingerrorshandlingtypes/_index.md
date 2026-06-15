---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Aspose.PDF for Java API Reference"
description: "Source XSLFO document can contain formatting errors."
type: docs
url: "/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/"
generated_from: "online-reference"
fetched_at: "2026-06-15T18:02:05+00:00"
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends System.Enum
```

Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handling of such formatting errors

## Fields {#fields}

| Field | Description |
| --- | --- |
| [TryIgnore](#TryIgnore) | In this case converter will be instructed to try proceed with conversion and ignore found formatting errors. |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | In this case conversion will be stopped immediately and exception will be thrown immediately after detecting of first formatting error |
| [InvokeCustomHandler](#InvokeCustomHandler) | This is the most agile method - custom code must supply (in WarningCallback property) special handler that will be called when formatting error detected. |

### TryIgnore {#TryIgnore}

```
public static final int TryIgnore
```

In this case converter will be instructed to try proceed with conversion and ignore found formatting errors. In this case success not guaranteed, serious problems can occure later in converter, anf in suck case will be thrown exception with list of found formatting errors.

### ThrowExceptionImmediately {#ThrowExceptionImmediately}

```
public static final int ThrowExceptionImmediately
```

In this case conversion will be stopped immediately and exception will be thrown immediately after detecting of first formatting error

### InvokeCustomHandler {#InvokeCustomHandler}

```
public static final int InvokeCustomHandler
```

This is the most agile method - custom code must supply (in WarningCallback property) special handler that will be called when formatting error detected. That handler can f.e. log or count errors etc and will supply decision whether processing can be continued for this or that error.
