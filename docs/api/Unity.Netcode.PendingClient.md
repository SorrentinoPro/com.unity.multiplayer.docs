---  
id: Unity.Netcode.PendingClient  
title: Unity.Netcode.PendingClient  
---

<div class="markdown level0 summary">

A class representing a client that is currently in the process of
connecting

</div>

<div class="markdown level0 conceptual">

</div>

<div class="inheritance">

##### Inheritance

<div class="level0">

System.Dynamic.ExpandoObject

</div>

<div class="level1">

System.Dynamic.ExpandoObject

</div>

</div>

<div class="inheritedMembers">

##### Inherited Members

<div>

Object.Equals(Object)

</div>

<div>

Object.Equals(Object, Object)

</div>

<div>

Object.GetHashCode()

</div>

<div>

Object.GetType()

</div>

<div>

Object.MemberwiseClone()

</div>

<div>

Object.ReferenceEquals(Object, Object)

</div>

<div>

Object.ToString()

</div>

</div>

##### **Namespace**: System.Dynamic.ExpandoObject

##### **Assembly**: MLAPI.dll

##### Syntax

``` lang-csharp
public class PendingClient
```

## 

### ClientId

<div class="markdown level1 summary">

The ClientId of the client

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

``` lang-csharp
public ulong ClientId { get; }
```

#### Property Value

| Type          | Description |
|---------------|-------------|
| System.UInt64 |             |

### ConnectionState

<div class="markdown level1 summary">

The state of the connection process for the client

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

``` lang-csharp
public PendingClient.State ConnectionState { get; }
```

#### Property Value

| Type                | Description |
|---------------------|-------------|
| PendingClient.State |             |
