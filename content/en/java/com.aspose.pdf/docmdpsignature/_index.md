---
title: "DocMDPSignature"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents the class of document MDP modification detection and prevention signature type."
type: docs
url: "/java/com.aspose.pdf/docmdpsignature/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/docmdpsignature/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:57:05+00:00"
---
**Inheritance:**
java.lang.Object

```
public final class DocMDPSignature
```

Represents the class of document MDP (modification detection and prevention) signature type.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [DocMDPSignature(Signature signature, int accessPermissions)](#DocMDPSignature-com.aspose.pdf.Signature-int-) | Initializes a new instance of the DocMDPSignature class. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getSignature()](#getSignature--) | Returns the signature object that used during signing. |
| [getAccessPermissions()](#getAccessPermissions--) | Returns the access permissions granted for this document. |

### DocMDPSignature(Signature signature, int accessPermissions) {#DocMDPSignature-com.aspose.pdf.Signature-int-}

```
public DocMDPSignature(Signature signature, int accessPermissions)
```

Initializes a new instance of the DocMDPSignature class.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| signature | [Signature](../../com.aspose.pdf/signature) | The signature object that used during signing. |
| accessPermissions | int | The access permissions granted for this document. |

### getSignature() {#getSignature--}

```
public Signature getSignature()
```

Returns the signature object that used during signing.

**Returns:**
[Signature](../../com.aspose.pdf/signature) - Signature object

### getAccessPermissions() {#getAccessPermissions--}

```
public int getAccessPermissions()
```

Returns the access permissions granted for this document.

**Returns:**
int - DocMDPAccessPermissions element
