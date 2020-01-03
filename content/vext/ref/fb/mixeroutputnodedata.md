---
title: MixerOutputNodeData
---
### Base Classes

[AudioGraphNodeData](AudioGraphNodeData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                    | Description                                                                                                                   |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| MixerOutputNodeData()                                                          | Create a new instance of this container type.                                                                                 |
| MixerOutputNodeData(MixerOutputNodeData other)                                 | Create a reference copy of an instance of the same type.                                                                      |
| MixerOutputNodeData([AudioGraphNodeData](AudioGraphNodeData) other)            | Upcast an instance of type [AudioGraphNodeData](AudioGraphNodeData) to [MixerOutputNodeData](MixerOutputNodeData).            |
| MixerOutputNodeData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [MixerOutputNodeData](MixerOutputNodeData). |

## Properties

| Name    | Type                                     | Description |
| ------- | ---------------------------------------- | ----------- |
| entries | [MixerOutputEntry](MixerOutputEntry)\[\] |             |

## Methods

| Type                                       | Name            | Parameters                                     |
| ------------------------------------------ | --------------- | ---------------------------------------------- |
| [MixerOutputNodeData](MixerOutputNodeData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [MixerOutputNodeData](MixerOutputNodeData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |