---
title: "TextDefaults.DefaultFontStrategy"
second_title: "Aspose.PDF for Java API Reference"
description: "Specifies type of text subsystem defaults"
type: docs
url: "/java/com.aspose.pdf/textdefaults.defaultfontstrategy/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/textdefaults.defaultfontstrategy/"
generated_from: "online-reference"
fetched_at: "2026-06-15T18:01:16+00:00"
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum

```
public static class TextDefaults.DefaultFontStrategy extends System.Enum
```

Specifies type of text subsystem defaults

## Fields {#fields}

| Field | Description |
| --- | --- |
| [SystemFont](#SystemFont) | Use default system font Helvetica, or it’s substituted analogue. |
| [PredefinedFont](#PredefinedFont) | Use default font that. |
| [ListOfFonts](#ListOfFonts) | Use default font from predefined list of Font instances. |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | The first font found will be used, containing all the necessary characters for the text. |

### SystemFont {#SystemFont}

```
public static final int SystemFont
```

Use default system font Helvetica, or it’s substituted analogue.

### PredefinedFont {#PredefinedFont}

```
public static final int PredefinedFont
```

Use default font that. Can be set using set/get PredefinedFont(Font) if PredefinedFont is null - will be used SystemFont

### ListOfFonts {#ListOfFonts}

```
public static final int ListOfFonts
```

Use default font from predefined list of Font instances. Can be set using setDefaultFonts(List of Font instances) Will be used the first found font that contains all required characters for text. If such font not found - will be used System font.

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}

```
public static final int TheFirstSuitableFoundFont
```

The first font found will be used, containing all the necessary characters for the text. All fonts found will be involved. If such font not found - will be used System font.
