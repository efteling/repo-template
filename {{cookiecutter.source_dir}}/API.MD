---
title: MinimalApi.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null v1.0
language_tabs:
  - shell: Shell
  - http: HTTP
  - javascript: JavaScript
  - ruby: Ruby
  - python: Python
  - php: PHP
  - java: Java
  - go: Go
toc_footers: []
includes: []
search: true
highlight_theme: darkula
headingLevel: 2

---

<!-- Generator: Widdershins v4.0.1 -->

<h1 id="minimalapi-core-version-1-0-0-0-culture-neutral-publickeytoken-null">MinimalApi.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null v1.0</h1>

> Scroll down for code samples, example requests and responses. Select a language for code samples from the tabs above or the mobile navigation menu.

<h1 id="minimalapi-core-version-1-0-0-0-culture-neutral-publickeytoken-null-minimalapi-core-version-1-0-0-0-culture-neutral-publickeytoken-null">MinimalApi.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null</h1>

## get__

`GET /`

> Example responses

> 200 Response

```
"string"
```

<h3 id="get__-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Success|string|

<aside class="success">
This operation does not require authentication
</aside>

## post__answers_{answer}

`POST /answers/{answer}`

<h3 id="post__answers_{answer}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|answer|path|string|true|none|

> Example responses

> 200 Response

```json
{
  "temperatureC": 0,
  "answerDescription": "string"
}
```

<h3 id="post__answers_{answer}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Success|[Answer](#schemaanswer)|

<aside class="success">
This operation does not require authentication
</aside>

## post__answers

`POST /answers`

> Body parameter

```json
{
  "temperatureC": 0,
  "answerDescription": "string"
}
```

<h3 id="post__answers-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|body|body|[Answer](#schemaanswer)|true|none|

> Example responses

> 200 Response

```json
{
  "id": 0,
  "created": true
}
```

<h3 id="post__answers-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Success|[CreateAnswerResponse](#schemacreateanswerresponse)|

<aside class="success">
This operation does not require authentication
</aside>

# Schemas

<h2 id="tocS_Answer">Answer</h2>
<!-- backwards compatibility -->
<a id="schemaanswer"></a>
<a id="schema_Answer"></a>
<a id="tocSanswer"></a>
<a id="tocsanswer"></a>

```json
{
  "temperatureC": 0,
  "answerDescription": "string"
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|temperatureC|integer(int32)|false|none|none|
|answerDescription|string¦null|false|none|none|

<h2 id="tocS_CreateAnswerResponse">CreateAnswerResponse</h2>
<!-- backwards compatibility -->
<a id="schemacreateanswerresponse"></a>
<a id="schema_CreateAnswerResponse"></a>
<a id="tocScreateanswerresponse"></a>
<a id="tocscreateanswerresponse"></a>

```json
{
  "id": 0,
  "created": true
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|id|integer(int32)|false|none|none|
|created|boolean|false|none|none|

