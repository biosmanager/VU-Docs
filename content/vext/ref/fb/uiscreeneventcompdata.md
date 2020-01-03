---
title: UIScreenEventCompData
---
### Base Classes

[UIComponentData](UIComponentData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                      | Description                                                                                                                       |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| UIScreenEventCompData()                                                          | Create a new instance of this container type.                                                                                     |
| UIScreenEventCompData(UIScreenEventCompData other)                               | Create a reference copy of an instance of the same type.                                                                          |
| UIScreenEventCompData([UIComponentData](UIComponentData) other)                  | Upcast an instance of type [UIComponentData](UIComponentData) to [UIScreenEventCompData](UIScreenEventCompData).                  |
| UIScreenEventCompData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UIScreenEventCompData](UIScreenEventCompData).                                      |
| UIScreenEventCompData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UIScreenEventCompData](UIScreenEventCompData). |

## Methods

| Type                                           | Name            | Parameters                                     |
| ---------------------------------------------- | --------------- | ---------------------------------------------- |
| [UIScreenEventCompData](UIScreenEventCompData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UIScreenEventCompData](UIScreenEventCompData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |