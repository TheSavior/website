---
id: version-7.0.0-babel-helper-wrap-function
title: @babel/helper-wrap-function
sidebar_label: babel-helper-wrap-function
original_id: babel-helper-wrap-function
---

## Example

**In**

```js
(function () {
}());
```

**Out**

```js
_wrapper(function () {
})();
```

## Usage

```js
import wrapFunction from "@babel/helper-wrap-function";

wrapFunction(nodePathOfTheFunction, nodeWhichReferencesToTheWrapper);
```

