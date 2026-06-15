---
title: "IInterruptMonitor"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents information about interruption."
type: docs
url: "/java/com.aspose.pdf.multithreading/iinterruptmonitor/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.multithreading/iinterruptmonitor/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:53:54+00:00"
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public interface IInterruptMonitor extends System.IDisposable
```

Represents information about interruption.

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getCancellationToken()](#getCancellationToken--) | Monitor’s cancellation token used for process interruption. |
| [interrupt()](#interrupt--) | Sends a request to interrupt operations. |

### getCancellationToken() {#getCancellationToken--}

```
public abstract CancellationTokenSource getCancellationToken()
```

Monitor’s cancellation token used for process interruption. By default each IInterruptMonitor generates its own cancellationSource

**Returns:**
[CancellationTokenSource](../../com.aspose.pdf.multithreading/cancellationtokensource) - CancellationTokenSource instance

### interrupt() {#interrupt--}

```
public abstract void interrupt()
```

Sends a request to interrupt operations.
