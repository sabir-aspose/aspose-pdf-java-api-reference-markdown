---
title: "RenditionOperation"
second_title: "Aspose.PDF for Java API Reference"
description: "The operation to perform when the action is triggered."
type: docs
url: "/java/com.aspose.pdf/renditionoperation/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/renditionoperation/"
generated_from: "online-reference"
fetched_at: "2026-06-15T18:00:22+00:00"
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum

```
public final class RenditionOperation extends System.Enum
```

The operation to perform when the action is triggered.

## Fields {#fields}

| Field | Description |
| --- | --- |
| [PlayStop](#PlayStop) | If no rendition is associated with the annotation, play the specified rendition, associating it with the annotation. |
| [Stop](#Stop) | Stop any rendition being played in association with the annotation. |
| [Pause](#Pause) | Pause any rendition being played in association with the annotation. |
| [Resume](#Resume) | Resume any rendition being played in association with the annotation. |
| [PlayResume](#PlayResume) | Play the specified rendition, associating it with the annotation. |
| [Undefined](#Undefined) | Operation not defined. |

### PlayStop {#PlayStop}

```
public static final int PlayStop
```

If no rendition is associated with the annotation, play the specified rendition, associating it with the annotation. If a rendition is already associated with the annotation, it shall be stopped, and the new rendition shall be associated with the annotation.

### Stop {#Stop}

```
public static final int Stop
```

Stop any rendition being played in association with the annotation.

### Pause {#Pause}

```
public static final int Pause
```

Pause any rendition being played in association with the annotation.

### Resume {#Resume}

```
public static final int Resume
```

Resume any rendition being played in association with the annotation.

### PlayResume {#PlayResume}

```
public static final int PlayResume
```

Play the specified rendition, associating it with the annotation. If a rendition is already associated with the annotation, resume the rendition if it is paused.

### Undefined {#Undefined}

```
public static final int Undefined
```

Operation not defined.
