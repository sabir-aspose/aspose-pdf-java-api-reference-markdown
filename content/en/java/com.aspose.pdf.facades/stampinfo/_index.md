---
title: "StampInfo"
second_title: "Aspose.PDF for Java API Reference"
description: "Class representing stamp information."
type: docs
url: "/java/com.aspose.pdf.facades/stampinfo/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.facades/stampinfo/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:53:48+00:00"
---
**Inheritance:**
java.lang.Object

```
public final class StampInfo
```

Class representing stamp information.

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getStampId()](#getStampId--) | Gets identifier of the stamp. |
| [getIndexOnPage()](#getIndexOnPage--) | Gets stamp index on the page. |
| [getStampType()](#getStampType--) | Gets stamp type (image / form). |
| [getRectangle()](#getRectangle--) | Gets rectangle where stamp is placed. |
| [getImageInternal()](#getImageInternal--) | Gets image of stamp. |
| [getImage()](#getImage--) | Gets image of stamp. |
| [getForm()](#getForm--) | Gets XForm of the stamp. |
| [getText()](#getText--) | Gets text in the stamp. |
| [getVisible()](#getVisible--) | Gets visibility of stamp. |

### getStampId() {#getStampId--}

```
public int getStampId()
```

Gets identifier of the stamp.

**Returns:**
int - int value

### getIndexOnPage() {#getIndexOnPage--}

```
public int getIndexOnPage()
```

Gets stamp index on the page.

**Returns:**
int - int value

### getStampType() {#getStampType--}

```
public StampType getStampType()
```

Gets stamp type (image / form).

**Returns:**
[StampType](../../com.aspose.pdf.facades/stamptype) - StampType element

### getRectangle() {#getRectangle--}

```
public Rectangle getRectangle()
```

Gets rectangle where stamp is placed.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle element

### getImageInternal() {#getImageInternal--}

```
public System.Drawing.Image getImageInternal()
```

Gets image of stamp. May be null if stamp does not contain images (for example for text stamp).

**Returns:**
[Image](../../com.aspose.ms.system.drawing/image) - Image object

### getImage() {#getImage--}

```
public BufferedImage getImage()
```

Gets image of stamp. May be null if stamp does not contain images (for example for text stamp).

**Returns:**
java.awt.image.BufferedImage - BufferedImage object

### getForm() {#getForm--}

```
public XForm getForm()
```

Gets XForm of the stamp.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm object

### getText() {#getText--}

```
public String getText()
```

Gets text in the stamp.

**Returns:**
java.lang.String - String value

### getVisible() {#getVisible--}

```
public boolean getVisible()
```

Gets visibility of stamp. If false then stamp is hidden (with HideStampById). Hidden stamp may be restored by ShowStampById.

**Returns:**
boolean - boolean value
