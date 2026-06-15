---
title: "IIndexBitmapConverter"
second_title: "Aspose.PDF for Java API Reference"
description: "This interface declared for customization algorithms of quantization."
type: docs
url: "/java/com.aspose.pdf/iindexbitmapconverter/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/iindexbitmapconverter/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:58:17+00:00"
---
```
public interface IIndexBitmapConverter
```

This interface declared for customization algorithms of quantization. Users can implement their own realization of this algorithms (for example algorithms based on unmanaged code).

## Methods {#methods}

| Method | Description |
| --- | --- |
| [get1BppImage(BufferedImage src)](#get1BppImage-java.awt.image.BufferedImage-) | Returns 1Bpp bitmap representation |
| [get4BppImage(BufferedImage src)](#get4BppImage-java.awt.image.BufferedImage-) | Returns 4Bpp bitmap representation |
| [get8BppImage(BufferedImage src)](#get8BppImage-java.awt.image.BufferedImage-) | Returns 4Bpp bitmap representation |

### get1BppImage(BufferedImage src) {#get1BppImage-java.awt.image.BufferedImage-}

```
public abstract BufferedImage get1BppImage(BufferedImage src)
```

Returns 1Bpp bitmap representation

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| src | java.awt.image.BufferedImage | Source bitmap. |

**Returns:**
java.awt.image.BufferedImage - Bitmap in 1 bpp image format.

### get4BppImage(BufferedImage src) {#get4BppImage-java.awt.image.BufferedImage-}

```
public abstract BufferedImage get4BppImage(BufferedImage src)
```

Returns 4Bpp bitmap representation

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| src | java.awt.image.BufferedImage | Source bitmap. |

**Returns:**
java.awt.image.BufferedImage - Bitmap in 4 bpp image format.

### get8BppImage(BufferedImage src) {#get8BppImage-java.awt.image.BufferedImage-}

```
public abstract BufferedImage get8BppImage(BufferedImage src)
```

Returns 4Bpp bitmap representation

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| src | java.awt.image.BufferedImage | Source bitmap. |

**Returns:**
java.awt.image.BufferedImage - Bitmap in 4 bpp image format.
