---
title: "TimestampSettings"
second_title: "Aspose.PDF for Java API Reference"
description: "Represents the ocsp settings using during signing process."
type: docs
url: "/java/com.aspose.pdf/timestampsettings/"
source_url: "https://reference.aspose.com/pdf/java/com.aspose.pdf/timestampsettings/"
generated_from: "online-reference"
fetched_at: "2026-06-15T18:01:37+00:00"
---
**Inheritance:**
java.lang.Object

```
public class TimestampSettings
```

Represents the ocsp settings using during signing process.

## Constructors {#constructors}

| Constructor | Description |
| --- | --- |
| [TimestampSettings(String serverUrl, String basicAuthCredentials)](#TimestampSettings-java.lang.String-java.lang.String-) | Initializes a new instance of the TimestampSettings class. |
| [TimestampSettings(String serverUrl, String basicAuthCredentials, int digestHashAlgorithm)](#TimestampSettings-java.lang.String-java.lang.String-int-) | Initializes a new instance of the TimestampSettings class. |

## Methods {#methods}

| Method | Description |
| --- | --- |
| [getServerUrl()](#getServerUrl--) | Gets the timestamp server url. |
| [setServerUrl(String value)](#setServerUrl-java.lang.String-) | Sets the timestamp server url. |
| [getBasicAuthCredentials()](#getBasicAuthCredentials--) | Gets the basic authentication credentials, Username and password are combined into a string “username:password”. |
| [setBasicAuthCredentials(String value)](#setBasicAuthCredentials-java.lang.String-) | Sets the basic authentication credentials, Username and password are combined into a string “username:password”. |
| [getDigestHashAlgorithm()](#getDigestHashAlgorithm--) | Gets/sets the digest algorithm for internal hash functions. |
| [setDigestHashAlgorithm(int value)](#setDigestHashAlgorithm-int-) | Gets/sets the digest algorithm for internal hash functions. |

### TimestampSettings(String serverUrl, String basicAuthCredentials) {#TimestampSettings-java.lang.String-java.lang.String-}

```
public TimestampSettings(String serverUrl, String basicAuthCredentials)
```

Initializes a new instance of the TimestampSettings class.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| serverUrl | java.lang.String | The timestamp server url. |
| basicAuthCredentials | java.lang.String | The basic authentication credentials, username and password are combined into a string “username:password”. |

### TimestampSettings(String serverUrl, String basicAuthCredentials, int digestHashAlgorithm) {#TimestampSettings-java.lang.String-java.lang.String-int-}

```
public TimestampSettings(String serverUrl, String basicAuthCredentials, int digestHashAlgorithm)
```

Initializes a new instance of the TimestampSettings class.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| serverUrl | java.lang.String | The timestamp server url. |
| basicAuthCredentials | java.lang.String | The basic authentication credentials, username and password are combined into a string “username:password”. |
| digestHashAlgorithm | int | The hash algorithm name, if it is omitted then sha1 is used. |

### getServerUrl() {#getServerUrl--}

```
public String getServerUrl()
```

Gets the timestamp server url.

**Returns:**
java.lang.String - String value

### setServerUrl(String value) {#setServerUrl-java.lang.String-}

```
public void setServerUrl(String value)
```

Sets the timestamp server url.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getBasicAuthCredentials() {#getBasicAuthCredentials--}

```
public String getBasicAuthCredentials()
```

Gets the basic authentication credentials, Username and password are combined into a string “username:password”.

**Returns:**
java.lang.String - String value

### setBasicAuthCredentials(String value) {#setBasicAuthCredentials-java.lang.String-}

```
public void setBasicAuthCredentials(String value)
```

Sets the basic authentication credentials, Username and password are combined into a string “username:password”.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getDigestHashAlgorithm() {#getDigestHashAlgorithm--}

```
public final int getDigestHashAlgorithm()
```

Gets/sets the digest algorithm for internal hash functions.

**Returns:**
int - DigestHashAlgorithm element

### setDigestHashAlgorithm(int value) {#setDigestHashAlgorithm-int-}

```
public final void setDigestHashAlgorithm(int value)
```

Gets/sets the digest algorithm for internal hash functions.

**Parameters:**

| Parameter | Type | Description |
| --- | --- | --- |
| value | int | DigestHashAlgorithm element |
