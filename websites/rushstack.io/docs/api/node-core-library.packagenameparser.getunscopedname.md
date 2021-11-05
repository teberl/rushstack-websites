---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [PackageNameParser](./node-core-library.packagenameparser.md) &gt; [getUnscopedName](./node-core-library.packagenameparser.getunscopedname.md)

## PackageNameParser.getUnscopedName() method

The parsed NPM package name without the scope.

<b>Signature:</b>

```typescript
getUnscopedName(packageName: string): string;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  packageName | string |  |

<b>Returns:</b>

string

## Remarks

For example, if the parsed input was " @ scope/example", then the name would be "example".
