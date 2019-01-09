[Home](./index) &gt; [@microsoft/node-core-library](./node-core-library.md) &gt; [PackageName](./node-core-library.packagename.md) &gt; [tryParse](./node-core-library.packagename.tryparse.md)

## PackageName.tryParse() method

This attempts to parse a package name that may include a scope component. The packageName must not be an empty string.

<b>Signature:</b>

```typescript
static tryParse(packageName: string): IParsedPackageNameOrError;
```

## Parameters

|  <p>Parameter</p> | <p>Type</p> | <p>Description</p> |
|  --- | --- | --- |
|  <p>packageName</p> | <p>`string`</p> |  |

<b>Returns:</b>

`IParsedPackageNameOrError`

an [IParsedPackageNameOrError](./node-core-library.iparsedpackagenameorerror.md) structure whose `error` property will be nonempty if the string could not be parsed.

## Remarks

This function will not throw an exception.
