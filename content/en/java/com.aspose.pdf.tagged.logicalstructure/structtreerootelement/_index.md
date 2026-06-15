---
title: "StructTreeRootElement"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents StructTreeRoot object in logical structure."
type: docs
url: "/java/com.aspose.pdf.tagged.logicalstructure/structtreerootelement/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.tagged.logicalstructure/structtreerootelement/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:55:42+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)

```
public final class StructTreeRootElement extends Element
```

Represents StructTreeRoot object in logical structure.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [StructTreeRootElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#StructTreeRootElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getIDTree()](#getIDTree--) |  |
| [getRoleMap()](#getRoleMap--) |  |
| [doPreSave()](#doPreSave--) |  |
| [doSave()](#doSave--) |  |
| [init()](#init--) |  |
| [createStructParents()](#createStructParents--) |  |
| [getStructParentsArray(IPdfNumber structParents)](#getStructParentsArray-com.aspose.pdf.engine.data.IPdfNumber-) |  |
| [getAllElements()](#getAllElements--) |  |
| [registrationObjectInParentTree(IPdfObject pdfObject)](#registrationObjectInParentTree-com.aspose.pdf.engine.data.IPdfObject-) |  |

### StructTreeRootElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#StructTreeRootElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}

```
public StructTreeRootElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| taggedContext | [TaggedContext](../../com.aspose.pdf.tagged/taggedcontext) |  |
| pdfEngineEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

### getIDTree() {#getIDTree--}

```
public final NamesTreeNode getIDTree()
```

**Returns:**
[NamesTreeNode](../../com.aspose.pdf.engine.commondata/namestreenode)

### getRoleMap() {#getRoleMap--}

```
public final IPdfDictionary getRoleMap()
```

**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary)

### doPreSave() {#doPreSave--}

```
public final void doPreSave()
```

### doSave() {#doSave--}

```
public final void doSave()
```

### init() {#init--}

```
public final void init()
```

### createStructParents() {#createStructParents--}

```
public final IPdfNumber createStructParents()
```

**Returns:**
[IPdfNumber](../../com.aspose.pdf.engine.data/ipdfnumber)

### getStructParentsArray(IPdfNumber structParents) {#getStructParentsArray-com.aspose.pdf.engine.data.IPdfNumber-}

```
public final IPdfArray getStructParentsArray(IPdfNumber structParents)
```

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| structParents | [IPdfNumber](../../com.aspose.pdf.engine.data/ipdfnumber) |  |

**Returns:**
[IPdfArray](../../com.aspose.pdf.engine.data/ipdfarray)

### getAllElements() {#getAllElements--}

```
public final System.Collections.Generic.List<Element> getAllElements()
```

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.tagged.logicalstructure.elements.Element>

### registrationObjectInParentTree(IPdfObject pdfObject) {#registrationObjectInParentTree-com.aspose.pdf.engine.data.IPdfObject-}

```
public final int registrationObjectInParentTree(IPdfObject pdfObject)
```

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| pdfObject | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) |  |

**Returns:**
int
