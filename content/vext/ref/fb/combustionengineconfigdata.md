---
title: CombustionEngineConfigData
---
### Base Classes

[EngineConfigData](EngineConfigData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                           | Description                                                                                                                                 |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| CombustionEngineConfigData()                                                          | Create a new instance of this container type.                                                                                               |
| CombustionEngineConfigData(CombustionEngineConfigData other)                          | Create a reference copy of an instance of the same type.                                                                                    |
| CombustionEngineConfigData([EngineConfigData](EngineConfigData) other)                | Upcast an instance of type [EngineConfigData](EngineConfigData) to [CombustionEngineConfigData](CombustionEngineConfigData).                |
| CombustionEngineConfigData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [CombustionEngineConfigData](CombustionEngineConfigData). |

## Methods

| Type                                                     | Name            | Parameters                                     |
| -------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [CombustionEngineConfigData](CombustionEngineConfigData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [CombustionEngineConfigData](CombustionEngineConfigData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |