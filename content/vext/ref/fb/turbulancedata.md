---
title: TurbulanceData
---
### Base Classes

[ProcessorData](ProcessorData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                               | Description                                                                                                         |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| TurbulanceData()                                                          | Create a new instance of this container type.                                                                       |
| TurbulanceData(TurbulanceData other)                                      | Create a reference copy of an instance of the same type.                                                            |
| TurbulanceData([ProcessorData](ProcessorData) other)                      | Upcast an instance of type [ProcessorData](ProcessorData) to [TurbulanceData](TurbulanceData).                      |
| TurbulanceData([EmitterComponentData](EmitterComponentData) other)        | Upcast an instance of type [EmitterComponentData](EmitterComponentData) to [TurbulanceData](TurbulanceData).        |
| TurbulanceData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [TurbulanceData](TurbulanceData). |

## Properties

| Name      | Type   | Description |
| --------- | ------ | ----------- |
| intensity | number |             |

## Methods

| Type                             | Name            | Parameters                                     |
| -------------------------------- | --------------- | ---------------------------------------------- |
| [TurbulanceData](TurbulanceData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [TurbulanceData](TurbulanceData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |