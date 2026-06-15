---
title: "CustomFontSubstitutionBase"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents a base class for custom font substitution strategy."
type: docs
url: "/java/com.aspose.pdf.text/customfontsubstitutionbase/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf.text/customfontsubstitutionbase/"
generated_from: "online-reference"
fetched_at: "2026-06-15T17:55:49+00:00"
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.text.FontSubstitution](../../com.aspose.pdf.text/fontsubstitution)

```
public class CustomFontSubstitutionBase extends FontSubstitution
```

Represents a base class for custom font substitution strategy.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [CustomFontSubstitutionBase()](#CustomFontSubstitutionBase--) |  |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont)](#trySubstitute-com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification-com.aspose.pdf.Font---) | Substitutes original font with another font. |

### CustomFontSubstitutionBase() {#CustomFontSubstitutionBase--}

```
public CustomFontSubstitutionBase()
```

### trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont) {#trySubstitute-com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification-com.aspose.pdf.Font---}

```
public boolean trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont)
```

Substitutes original font with another font.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| originalFontSpecification | [OriginalFontSpecification](../../com.aspose.pdf.text/originalfontspecification) | Original font specification. |
| substitutionFont | [Font[]](../../com.aspose.pdf/font) | Substitution font. |

---

The class CustomFontSubstitutionBase should be inherited to implement custom font substitution logic. TrySubstitute method should be overridden properly: Must return true in case substitution is required. substitutionFont must be set to valid Font object. Must return false in case no substitution is required. substitutionFont may be set to null. |

**Returns:**
boolean - True in case substitution was successful.
