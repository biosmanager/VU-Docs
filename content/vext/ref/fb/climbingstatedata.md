---
title: ClimbingStateData
---
### Base Classes

[CharacterStateData](CharacterStateData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                  | Description                                                                                                               |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| ClimbingStateData()                                                          | Create a new instance of this container type.                                                                             |
| ClimbingStateData(ClimbingStateData other)                                   | Create a reference copy of an instance of the same type.                                                                  |
| ClimbingStateData([CharacterStateData](CharacterStateData) other)            | Upcast an instance of type [CharacterStateData](CharacterStateData) to [ClimbingStateData](ClimbingStateData).            |
| ClimbingStateData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [ClimbingStateData](ClimbingStateData). |

## Properties

| Name                       | Type   | Description |
| -------------------------- | ------ | ----------- |
| lateralInputScale          | number |             |
| downAngleLimit             | number |             |
| dropOffAngle               | number |             |
| attractionVelocity         | number |             |
| pushAwayVelocity           | number |             |
| climbHeightOffset          | number |             |
| climbOffVerticalDistance   | number |             |
| climbOffVerticalTime       | number |             |
| climbOffHorizontalDistance | number |             |
| climbOffHorizontalTime     | number |             |

## Methods

| Type                                   | Name            | Parameters                                     |
| -------------------------------------- | --------------- | ---------------------------------------------- |
| [ClimbingStateData](ClimbingStateData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [ClimbingStateData](ClimbingStateData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |