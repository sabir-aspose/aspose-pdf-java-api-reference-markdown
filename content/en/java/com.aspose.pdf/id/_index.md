---
title: "Id"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents file identifier structure."
type: docs
url: "/java/com.aspose.pdf/id/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/id/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:58:15+00:00"
---
**Inheritance:**
java.lang.Object

```
public class Id
```

Represents file identifier structure.

---

```
Document doc = new Document("example.pdf");
 String original = doc.getId().getOriginal();
 String modified = doc.getId().getModified();
```

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getOriginal()](#getOriginal--) | Permanent identifier based on the contents of the document at the time it was originally created. |
| [getModified()](#getModified--) | Changing identifier based on the document’s contents at the time it was last updated. |

### getOriginal() {#getOriginal--}

```
public String getOriginal()
```

Permanent identifier based on the contents of the document at the time it was originally created.

**Returns:**
java.lang.String - String value

### getModified() {#getModified--}

```
public String getModified()
```

Changing identifier based on the document’s contents at the time it was last updated.

**Returns:**
java.lang.String - String value
