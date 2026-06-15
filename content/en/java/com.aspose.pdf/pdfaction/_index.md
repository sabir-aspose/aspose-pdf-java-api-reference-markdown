---
title: "PdfAction"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents Action in PDF document"
type: docs
url: "/java/com.aspose.pdf/pdfaction/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/pdfaction/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:59:44+00:00"
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.pdf.IAppointment](../../com.aspose.pdf/iappointment)

```
public abstract class PdfAction implements IAppointment
```

Represents Action in PDF document

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [PdfAction()](#PdfAction--) |  |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getNext()](#getNext--) | Next actions in sequence. |
| [getECMAScriptString()](#getECMAScriptString--) | Gets string for ECMAScript Action. |

### PdfAction() {#PdfAction--}

```
public PdfAction()
```

### getNext() {#getNext--}

```
public ActionCollection getNext()
```

Next actions in sequence.

**Returns:**
[ActionCollection](../../com.aspose.pdf/actioncollection) - ActionCollection object

### getECMAScriptString() {#getECMAScriptString--}

```
public final String getECMAScriptString()
```

Gets string for ECMAScript Action.

**Returns:**
java.lang.String - Return string for JS entry for ECMAScript Action or null else.
