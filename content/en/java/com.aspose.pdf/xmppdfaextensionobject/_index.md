---
title: "XmpPdfAExtensionObject"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents the base class for field property value type instances."
type: docs
url: "/java/com.aspose.pdf/xmppdfaextensionobject/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/xmppdfaextensionobject/"
generated_from: "online-reference"
fetched_at: "2026-06-15T18:02:00+00:00"
---
**Inheritance:**
java.lang.Object

```
public abstract class XmpPdfAExtensionObject
```

Represents the base class for field, property, value type instances.

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getDescription()](#getDescription--) | Gets the description. |
| [getValue()](#getValue--) | Gets the value. |
| [setValue(String value)](#setValue-java.lang.String-) | Sets the value. |
| [getXmlInternal(System.Xml.XmlDocument xmlDocument)](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent object in xml tree. |
| [getXml_(System.Xml.XmlDocument xmlDocument)](#getXml--com.aspose.ms.System.Xml.XmlDocument-) | Returns the list of xml elements that represent object in xml tree. |

### getDescription() {#getDescription--}

```
public String getDescription()
```

Gets the description.

**Returns:**
java.lang.String - String

### getValue() {#getValue--}

```
public String getValue()
```

Gets the value.

**Returns:**
java.lang.String - String

### setValue(String value) {#setValue-java.lang.String-}

```
public void setValue(String value)
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String |

### getXmlInternal(System.Xml.XmlDocument xmlDocument) {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}

```
public abstract System.Collections.Generic.List<System.Xml.XmlElement> getXmlInternal(System.Xml.XmlDocument xmlDocument)
```

Returns the list of xml elements that represent object in xml tree.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | The source xml document. |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Xml.XmlElement> - The list of xml elements.

### getXml_(System.Xml.XmlDocument xmlDocument) {#getXml--com.aspose.ms.System.Xml.XmlDocument-}

```
public abstract List<System.Xml.XmlElement> getXml_(System.Xml.XmlDocument xmlDocument)
```

Returns the list of xml elements that represent object in xml tree.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | The source xml document. |

**Returns:**
java.util.List<com.aspose.ms.System.Xml.XmlElement> - The list of xml elements.
