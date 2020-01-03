---
title: DebrisHavokInfo
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                            | Description                                              |
| -------------------------------------- | -------------------------------------------------------- |
| DebrisHavokInfo()                      | Create a new instance of this structure type.            |
| DebrisHavokInfo(DebrisHavokInfo other) | Create a reference copy of a structure of the same type. |

## Properties

| Name         | Type                     | Description |
| ------------ | ------------------------ | ----------- |
| havokAsset   | [HavokAsset](HavokAsset) |             |
| reserveCount | number                   |             |

## Methods

| Type                               | Name            | Parameters |
| ---------------------------------- | --------------- | ---------- |
| [DebrisHavokInfo](DebrisHavokInfo) | [Clone](#clone) |            |

### Clone

> [DebrisHavokInfo](DebrisHavokInfo) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone).