---
title: BaseEmitterData
---
### Base Classes

[ProcessorData](ProcessorData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                | Description                                                                                                           |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BaseEmitterData()                                                          | Create a new instance of this container type.                                                                         |
| BaseEmitterData(BaseEmitterData other)                                     | Create a reference copy of an instance of the same type.                                                              |
| BaseEmitterData([ProcessorData](ProcessorData) other)                      | Upcast an instance of type [ProcessorData](ProcessorData) to [BaseEmitterData](BaseEmitterData).                      |
| BaseEmitterData([EmitterComponentData](EmitterComponentData) other)        | Upcast an instance of type [EmitterComponentData](EmitterComponentData) to [BaseEmitterData](BaseEmitterData).        |
| BaseEmitterData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [BaseEmitterData](BaseEmitterData). |

## Properties

| Name         | Type                               | Description |
| ------------ | ---------------------------------- | ----------- |
| emitterAsset | [EmitterDocument](EmitterDocument) |             |

## Methods

| Type                               | Name            | Parameters                                     |
| ---------------------------------- | --------------- | ---------------------------------------------- |
| [BaseEmitterData](BaseEmitterData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [BaseEmitterData](BaseEmitterData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |