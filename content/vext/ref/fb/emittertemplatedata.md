---
title: EmitterTemplateData
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                    | Description                                                                                                                   |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| EmitterTemplateData()                                                          | Create a new instance of this container type.                                                                                 |
| EmitterTemplateData(EmitterTemplateData other)                                 | Create a reference copy of an instance of the same type.                                                                      |
| EmitterTemplateData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [EmitterTemplateData](EmitterTemplateData). |

## Properties

| Name                                | Type                              | Description |
| ----------------------------------- | --------------------------------- | ----------- |
| pointLightIntensity                 | [Vec4](/vext/ref/shared/class/Vec4) |             |
| pointLightPivot                     | [Vec3](/vext/ref/shared/class/Vec3) |             |
| pointLightColor                     | [Vec3](/vext/ref/shared/class/Vec3) |             |
| maxCount                            | number                            |             |
| name                                | string                            |             |
| timeScale                           | number                            |             |
| lifetimeFrameCount                  | number                            |             |
| lifetime                            | number                            |             |
| rootProcessor                       | [ProcessorData](ProcessorData)    |             |
| visibleAfterDistance                | number                            |             |
| zOcclusionLookup                    | number\[\]                        |             |
| emittableType                       | [EmittableType](EmittableType)    |             |
| mesh                                | [MeshAsset](MeshAsset)            |             |
| distanceScaleNearValue              | number                            |             |
| pointLightRadius                    | number                            |             |
| vertexPixelLightingBlendFactor      | number                            |             |
| globalLocalNormalBlendFactor        | number                            |             |
| softParticlesFadeDistanceMultiplier | number                            |             |
| lightWrapAroundFactor               | number                            |             |
| lightMultiplier                     | number                            |             |
| distanceScaleFarValue               | number                            |             |
| pointLightRandomIntensityMin        | number                            |             |
| meshCullingDistance                 | number                            |             |
| pointLightRandomIntensityMax        | number                            |             |
| maxSpawnDistance                    | number                            |             |
| minScreenArea                       | number                            |             |
| distanceScaleLength                 | number                            |             |
| pointLightMaxClamp                  | number                            |             |
| particleCullingFactor               | number                            |             |
| pointLightMinClamp                  | number                            |             |
| followSpawnSource                   | bool                              |             |
| repeatParticleSpawning              | bool                              |             |
| emissive                            | bool                              |             |
| exclusionVolumeCullEnable           | bool                              |             |
| transparencySunShadowEnable         | bool                              |             |
| forceFullRes                        | bool                              |             |
| localSpace                          | bool                              |             |
| opaque                              | bool                              |             |
| actAsPointLight                     | bool                              |             |
| killParticlesWithEmitter            | bool                              |             |
| forceNiceSorting                    | bool                              |             |

## Methods

| Type                                       | Name            | Parameters                                     |
| ------------------------------------------ | --------------- | ---------------------------------------------- |
| [EmitterTemplateData](EmitterTemplateData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [EmitterTemplateData](EmitterTemplateData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |