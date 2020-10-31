---
uid: Microsoft.Quantum.Arrays.Exclude
title: Exclude function
ms.date: 10/30/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Arrays
qsharp.name: Exclude
qsharp.summary: >-
  Returns an array containing the elements of another array,
  excluding elements at a given list of indices.
---

# Exclude function

Namespace: [Microsoft.Quantum.Arrays](xref:Microsoft.Quantum.Arrays)

Package: [](https://nuget.org/packages/)


Returns an array containing the elements of another array,

```qsharp
function Exclude<'T> (remove : Int[], array : 'T[]) : 'T[]
```


## Input

### remove : [Int](xref:microsoft.quantum.lang-ref.int)[]

An array of indices denoting which elements should be excluded


### array : 'T[]

Array of which the values in the output array are taken.



## Output : 'T[]

An array `output` such that `output[0]` is the first element

## Type Parameters

### 'T

The type of the array elements.