---
uid: Microsoft.Quantum.Chemistry.JordanWigner.JordanWignerBlockEncodingGeneratorSystem
title: JordanWignerBlockEncodingGeneratorSystem function
ms.date: 10/26/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Chemistry.JordanWigner
qsharp.name: JordanWignerBlockEncodingGeneratorSystem
qsharp.summary: >-
  Converts a Hamiltonian described by `JWOptimizedHTerms`
  to a `GeneratorSystem` expressed in terms of the Pauli
  `GeneratorIndex`.
---

# JordanWignerBlockEncodingGeneratorSystem function

Namespace: [Microsoft.Quantum.Chemistry.JordanWigner](xref:Microsoft.Quantum.Chemistry.JordanWigner)

Package: [](https://nuget.org/packages/)


Converts a Hamiltonian described by `JWOptimizedHTerms`to a `GeneratorSystem` expressed in terms of the Pauli`GeneratorIndex`.

```qsharp
function JordanWignerBlockEncodingGeneratorSystem (data : Microsoft.Quantum.Chemistry.JordanWigner.JWOptimizedHTerms) : Microsoft.Quantum.Simulation.GeneratorSystem
```


## Input

### data : [JWOptimizedHTerms](xref:Microsoft.Quantum.Chemistry.JordanWigner.JWOptimizedHTerms)

Description of Hamiltonian in `JWOptimizedHTerms` format.



## Output : [GeneratorSystem](xref:Microsoft.Quantum.Simulation.GeneratorSystem)

Representation of Hamiltonian as `GeneratorSystem`.