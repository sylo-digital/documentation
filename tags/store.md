---
title: {store} tags
description: Creates, deletes, or manipulates key-value variables.
published: 1
date: 2022-02-27T00:00:00.000Z
tags:
editor: markdown
dateCreated: 2022-01-24T16:12:52.291Z
---

# `{store}` tags

Tags used to keep values and data across invocations. `{perset}` and `{perget}` are analogs from v8.

```
{store.set;mykey;"This is a string"}
{store.has;mykey}  // true
{store.get;mykey}  // "This is a string"
{store.delete;mykey}
{store.has;mykey}  // false
```

## `{store.set;key;value}`

Adds an item to the store. `value` can be an object, array, string, number, etc. `key` will be coerced to a string.

## `{store.get;key}`

Gets an item from the store.

## `{store.delete;key}`

Deletes an item from the store.

## `{store.has;key}`

Checks if the store has a key.
